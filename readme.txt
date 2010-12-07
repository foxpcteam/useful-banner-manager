=== Useful Banner Manager ===
Contributors: s_ruben
Donate link: http://rubensargsyan.com/donate/
Tags: banner manager, ads manager, banners, ads, advertisement, buddypress
Requires at least: 2.9
Tested up to: 3.0.2

This banner manager plugin helps to manage the banners easily over the WordPress blog. It works with BuddyPress too.

== Description ==

There are many WordPress blogs which have or need to have banners on them. So a banner manager plugin is very useful for those blogs. This plugin is created for it. The plugin helps to manage the banners over the Wordpress blog. It is very easy to use. Try it and be assured.

P.S.

Wishing you to earn much money by banners advertising. :)

[Plugin Homepage](http://rubensargsyan.com/wordpress-plugin-useful-banner-manager)

== Installation ==

1. Download useful-banner-manager.zip, unzip it and upload the useful-banner-manager directory (including all files within) to the /wp-content/plugins/ directory.
2. Activate the plugin through the Plugins menu in WordPress.
3. Go to "Banner Manager" panel and add banners.
4. To show the banners in the sidebar, go to the "Appearance"->"Widgets" panel and drag-and-drop the "UBM banners" box into your sidebar, configure options and save them.
5. To show the banners in a post or a page, add [useful_banner_manager banners=2,6 count=1] (where the numbers 2 and 6 (banners=2,6) are the IDs of the banners which would be shown, the number 1 (count=1) is the count of the banners which would be shown) into the post or the page.
6. Also the banners can be shown by adding `<?php if(function_exists("useful_banner_manager_banners")){ useful_banner_manager_banners("2,6",1); } ?>` (where the first argument ("2,6") is a string of the banners' IDs, separated by commas, and the second argument is the banners' count which would be shown).

== Frequently Asked Questions ==

For questions contact with the plugin author - [Ruben Sargsyan](http://rubensargsyan.com/contact).

== Screenshots ==

1. Administration Interface

== Changelog ==

= 1.0 =
* First release.