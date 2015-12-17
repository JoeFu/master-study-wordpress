# Overview
A courses management system built by Wordpress v4.3.1 and MasterStudy Theme 1.4.1

# How to install by wordpress
1. Install Wordpress and install masterstudy theme
2. Update all plugin

# How to install by git
1. Checkout source: git clone https://github.com/rinodung/master-study-wordpress.git
2. Export database from wp-resources/*.sql (change some value wp_options: siteurl,home)
3. Rename wp-config.sample.php => wp-config.php
4. Edit some option in wp-config.php(database, domain...)


# Project Structure
----wp-admin

----wp-content

----wp-includes

----wp-resources(database, theme source, plugin source, document...)

# Backup database
mysqldump  -u rinodung c9 > version1.4.1.sql  
