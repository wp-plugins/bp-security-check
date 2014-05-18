=== BuddyPress Security Check ===
Contributors: bungeshea
Tags: math, registration, buddypress, security, anti-spam
Tested up to: 3.9.1
Stable tag: 1.2.0
License: MIT
License URI: http://opensource.org/licences/MIT
Donate link: http://bungeshea.com/donate/

Help combat spam registrations by forcing the user to answer a simple math sum while registering for your BuddyPress-powered site

== Description ==

This plugin will add a field to the BuddyPress registration form where the user will need to answer simple math sum before registering. This is an effort to stop spam bots from registering on your site. The math sum will be composed of adding or subtracting two random numbers between 0 and 10 (inclusive).

You can learn more at the [plugin's website](http://bungeshea.com/plugins/bp-security-check/), or contribute to this plugin's development on [GitHub](https://github.com/bungeshea/bp-security-check)

== Installation ==

This plugin extends the functionality of [BuddyPress](http://wordpress.org/plugins/buddypress), which must be installed for this plugin to work

1. Upload `bp-security-check.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the __(Plugins > Installed Plugins)__ menu in WordPress
3. Done! The plugin has no settings to configure, just install and activate

== Changelog ==

= 1.2.0 =
* Added Hungarian translation by Laszlo Espadas
* Added Brazilian Portuguese translation by Renato Alves
* Saved sum information in database instead of hidden fields in an attempt to prevent bots
* Code refactoring

= 1.1.0.1 =
* Fixed bug preventing the plugin from loading

= 1.1.0 =
* Updated to support translations
* Use mt_rand() function instead of rand()
* Add code documentation
* Use proper class methods, not completely static
* Ensure that the sum never equals 0

= 1.0.1 =
* Remove buggy multiplication and division functionality

= 1.0.0 =
* Stable version release

== Upgrade Notice ==

= 1.2.0 =
New translations plus fixes to prevent bots

= 1.1.0.1 =
Fixed bug preventing the plugin from loading

= 1.1.0 =
Updated to support translations

= 1.0.1 =
Quick patch to remove buggy multiplication and division functionality
