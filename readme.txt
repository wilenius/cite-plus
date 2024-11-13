=== Cite Plus ===
Contributors: EnigmaWeb & Heikki Wilenius
Tags: Cite, cite, reference, citation, referencing, Coauthors Plus, DOI
Requires at least: 3.1
Tested up to: 6.7
Stable branch: main
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Help readers know how to cite your article correctly

== Description ==

Help readers know how to cite your article correctly. Use Cite plugin to display a box at the bottom of each page/post with reference information. Add to any page/post using shortcode `[cite]`

= Key Features =

*	Simple & lightweight
*	Dynamically generate tags such as site name, post title, permalink, publication date, last accessed date
*   Works in all major browsers - IE7, IE8, IE9, Safari, Firefox, Chrome
*	Add to any page using shortcode `[cite]`
* If a DOI is defined for the post, it is displayed instead of the page URL
* If the Coauthors Plus plugin is installed, and the post has more than one authors, all the authors are displayed in the reference information box.


== Installation ==

1. Upload the `cite` folder to the `/wp-content/plugins/` directory
1. Activate the Cite plugin through the WordPress 'Plugins' dashboard.
1. Configure the plugin by going to the `Cite` tab that appears in your admin menu.
1. Add to any page using shortcode `[cite]`
 
== Frequently Asked Questions ==

= Who is this plugin for? =

Cite plugin is made for academics or other people that publish scholarly articles using WordPress.  It allows them to easily add reference information with dynamic tags such as permalink or article title generated automatically.

= How can I customise the design? =

The plugin has some very basic styling which should work for most users, but if you want to customise it further you can do that easily via your theme CSS.

= Can I use Cite plugin in my Language? =

Yes, the plugin is internationalized and ready for translation. If you would like to help with a translation please [contact me](http://www.enigmaplugins.com/contact)

= Where can I get support for this plugin? =

If you've tried all the obvious stuff and it's still not working please request support via the forum.


== Screenshots ==

1. The Cite settings screen in WP Admin
2. An example of Cite in action

== Changelog ==

= 1.2.3 =
* Added support for DOIs and the Coauthors Plus plugin

= 1.2.2 =
* Fixed {date} template tag to get last accessed date (today's date)

= 1.2.1 =
* Added support for author name
* Updated default cite text
* Added reference samples
* Thank you to @jackdougherty for contributing these improvements

= 1.2 =
* Wrapped function displayTodaysDate in an if statement to avoid calling the function if it is already active 

= 1.1 =
* Added publication date template tag

= 1.0 =
* Initial release

== Upgrade Notice ==

= 1.2.2 =
* Fixed {date} template tag to get last accessed date (today's date)

= 1.2.1 =
* Added support for author name
* Updated default cite text
* Added reference samples
* Thank you to @jackdougherty for contributing these improvements

= 1.2 =
* Wrapped function displayTodaysDate in an if statement to avoid calling the function if it is already active 

= 1.1 =
* Added publication date template tag

= 1.0 =
* Initial release
