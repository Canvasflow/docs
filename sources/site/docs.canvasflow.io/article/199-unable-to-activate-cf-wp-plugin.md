# Source: https://docs.canvasflow.io/article/199-unable-to-activate-cf-wp-plugin

# Problems Activating the CF-WP Plugin

If you experience an error when attempting to activate the Canvasflow for WordPress plugin, it's very likely that your MySQL storage engine is configured to use MyISAM. 

The Canvasflow plugin uses _referential integrity_, which involves the use of foreign keys (RDBMS) and relationship constraints. The MyISAM engine does **not** support this feature, hence why it fails to activate. To correct this, the MySQL storage engine for two tables must be converted to InnoDB.

## Are You Using MyISAM or InnoDB?

If you are running a recently created WordPress site, it's likely to already be configured for the InnoDB MySQL storage engine. Older WordPress sites using MyISAMK will benefit in terms of reliability and performance from being converted. Some sites may even have mixed MyISAM and InnoDB tables, which again would be improved by conversion. Follow these steps to see how your WordPress site is currently configured.

1. Login to phpMyAdmin to view your mySQL database.
2. Click the `Type` column's header to sort by the engine types your tables are using. In the example below, you can see that two of the tables are still using MyISAM.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/5b5f3b1b2c7d3a03f89d23dc/file-qysZiD1daF.jpg)

Alternatively, you could run a query to see if any myISAM tables exist. Enter the following, remembering to replace ‘database’ with your own database's name.

`SELECT TABLE_NAME, ENGINE FROM information_schema.TABLES WHERE TABLE_SCHEMA = 'database' and ENGINE = 'myISAM'`

## Convert MyISAM to InnoDB

You can convert MyISAM tables to InnoDB easily. The example below uses the `wp_posts` table. Run the ALTER command to convert to InnoDB storage engine.

`ALTER TABLE wp_posts ENGINE=InnoDB;`

### Notes

1. Before attempting conversion to InnoDB, ensure you are running MySQL 5.6.4 or higher. Issues with unsupported full-text indexing may otherwise be encountered.

phpMyAdmin may be used to convert tables manually. By clicking on the myISAM table, then the `Operations` tab, the 'Storage Engine' dropdown will allow you to select `InnoDB` , as shown below.

_![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/571df1d49033600cce434499/images/5b5f3b2d2c7d3a03f89d23de/file-9SSXHsI3fB.jpg)_

Upon conversion of all required tables to InnoDB, please re-activate the plugin.

### Notes

1. Always backup your MySQL database before running any commands on it .

Still need help? [Contact Us](https://docs.canvasflow.io/article/199-unable-to-activate-cf-wp-plugin#) [Contact Us](https://docs.canvasflow.io/article/199-unable-to-activate-cf-wp-plugin#)

Last updated on June 30, 2025

No results found