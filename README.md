# Category-Cubcategory-Class
<pre>
CREATE TABLE IF NOT EXISTS `__category` (
  `id` int(7) NOT NULL AUTO_INCREMENT,
  `name` varchar(64) COLLATE utf8_general_ci NOT NULL,
  `parent_id` int(7) NOT NULL,
  `isset` int(1) NOT NULL DEFAULT '1',
  PRIMARY KEY (`id`),
  UNIQUE KEY `name` (`name`)
) ENGINE=InnoDB  DEFAULT CHARSET=utf8 COLLATE=utf8_general_ci AUTO_INCREMENT=18 ;
</pre>
