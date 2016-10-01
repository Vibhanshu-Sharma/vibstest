Please run this Sql Query or create `meta_title` column in table `cms_page` varchar(255). And After that upload the module files. Refreshed Cache and Re-Indexed .

ALTER TABLE `cms_page`  ADD `meta_title` VARCHAR(255) NOT NULL  AFTER `custom_theme_to`;
