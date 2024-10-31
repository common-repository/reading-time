=== Reading Time ===
Contributors: whiletrue
Donate link: https://www.whiletrue.it/
Tags: reading time, estimate time, reading, time, word count 
Requires at least: 2.9+
Requires PHP: 7.0
Tested up to: 6.5
Stable tag: 1.2.21

Reading Time shows the estimated reading time and puts an animated progress bar inside the post. 

== Description ==
Reading Time shows the estimated reading time of the post, in seconds or minutes. 
The estimate is automatic; a custom value for a single post can be inserted using a Custom Field named "readingtime".

For more info: https://www.whiletrue.it/reading-time-for-wordpress/

== Installation ==
1. Upload `reading_time.php` and `unisntall.php` into the `/wp-content/plugins/reading_time` directory
2. Set your favourite values in the `Settings->Reading Time` menu in Wordpress
3. Activate the plugin through the `Plugins` menu in WordPress
4. Enjoy!

== Frequently Asked Questions ==
= How is the estimation done? =
The estimation is based on the "speed" value stored in the settings menu.
The value for speed should be chosen between a span of 150 words per minute (slightly slower than average) to 250 words per minute (slightly higher than average); if not set, a default value of 200 is used.

== Screenshots ==
1. Sample content with the progress bar almost filled


== Changelog ==

= 1.2.21 =
* Added: New progress bar display setting
* Fixed: Settings sanitization
* Plugin tested up WordPress 6.5

= 1.1.0 =
* Added: Default settings value
* Added: New position setting, above or below the post
* Added: Uninstall function

= 1.0.0 =
Initial version


== Upgrade Notice == 

= 1.2.19 =
No upgrade issues known

= 1.0.0 =
Initial version
