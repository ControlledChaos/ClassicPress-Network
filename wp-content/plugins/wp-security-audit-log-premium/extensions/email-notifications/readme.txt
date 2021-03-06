=== Email Notifications for WP Security Audit Log ===
Contributors: WPWhiteSecurity, robert681
Plugin URI: http://www.wpsecurityauditlog.com/extensions/wordpress-email-notifications-add-on/
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl.html
Requires at least: 3.6
Tested up to: 4.7.3
Stable tag: 2.2.1

Get Notified Instantly via Email when Important Changes are Made on Your WordPress.

== Description ==
Email Notifications for WP Security Audit Log is a premium add-on to [WP Security Audit Log WordPress plugin](https://wordpress.org/plugins/wp-security-audit-log/) which allows you to configure triggers so once a change happens on your WordPress or WordPress multisite you are notified instantly via email. It also has built-in notifications.

== Installation ==

1. Upload the `email-notifications-wsal` folder to the `/wp-content/plugins/` directory
2. Activate the Email Notifications for WP Security Audit Log plugin from the 'Plugins' menu in the WordPress Administration Screens
3. Access the extension's configuration to create new notifications from the Email Notifications entry in the WP Security Audit Log plugin menu

== Changelog ==

= 2.2.1 (2017-09-05) =
  * Fixed issue in wizard, which was failing to retrieve list of alerts.
  
= 2.2.0 (2017-03-22) =
  * New feature to allow users to modify the email templates.
  * Included Count option in some alerts so users can create notification for example for when there are X amount of failed logins.
  * Usernames can be used instead of emails addresses when configuring email notifications.
  * Every email notification can have its own custom email notification.

= 2.1.3 (2017-03-01) =
  * Support for custom WordPress user roles (can now be used in trigger builder)
  * Support for Custom post types with prefix (can now be used in trigger builder)
  
= 2.1.2 (2016-11-14) =
  * Added Post Type option in trigger builder menu, allowing user to monitor a specific post type.

= 2.1.1 (2016-11-09) =
  * Email notifications generated by the Email Notifications Add-ons will now use the timestamp and date and time format as configured in WordPress.
  * Added new setting in trigger builder for time configuration (user can specify AM/PM if such time format is used in WordPress).
  * Added dynamic help text in the configuration trigger date setting to instruct user what date format should be used (as configured in WordPress).

= 2.1.0 (2016-09-20) =
* **New Feature**
	* Created a wizard that can be used to create new email notifications, making the plugin more user friendly.		
	
= 2.0.1 (2016-07-13) =
	* Updated email module to support different FROM email address - configurable from main plugin.

= 2.0.0 (2015-10-27) [Release Notes](http://www.wpsecurityauditlog.com/) =
* **New Features**
	* Support for multiple email addresses in email notifications
	* Added ability to create Email notitication trigger by site on multisite

* **New Built-In Alerts for:**
	* When a user logs in
	* New user is created
	* User changes own password or password of another user
	* User's role is changed
	* Content (posts, pages and custom post types) is published or changed
	* First time user logs in
	* New plugin is installed or activated
	* Plugin file is modified
	* A critical alert is generated
	
= 1.2.1 (2015-10-08) =
	* Updated text of notification when WSAL is offline
	
= 1.2.0 (2015-09-09) =
	* Updated plugin database connector
	* Support for new add-on External DB Connector

= 1.1.1 (2015-08-05) =
	* Renamed Add-On
	* Updated links to new website

= 1.1.0 (2015-07-16) =
	* Updated plugin to use new database connector in WP Security Audit Log

= 1.0 (2014-08-12) =
	* Initial release of WSAL Notifications extension
