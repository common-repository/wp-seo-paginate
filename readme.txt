=== WP-SEO-Paginate ===
Contributors: masdiblogs
Plugin Site: http://onlinewebapplication.com/
Donate link: http://onlinewebapplication.com/onlinewebapplication-com-donation/
Tags: navigation, pages, pagination, paging, paginate, comments paginate, seo, seo-paginate, paginate, navigation, page, wp-paginate, comments, rtl
Requires at least: 3.0
Tested up to: 3.8
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
	
Provides users with better and simple navigation interface.

== Description ==
<br />
[Author Site](http://onlinewebapplication.com)|
[Plugin Home Page](http://onlinewebapplication.com/2011/10/wp-seo-paginate.html)
<br />
<br />
Replaces the basic paging style with a simple paging navigation interface. WP-SEO-Paginate is a simple and flexible pagination plugin which provides users with better navigation on your WordPress site. In addition to increasing the user experience for your visitors, pagination also increases the SEO of your site by providing more links to your content. WP-SEO-Paginate can also be used to paginate post comments! Pagination for easier navigation on your WordPress

Feature:

1. Replaces the basic ? Older posts | Newer posts ? links with a simple paging navigation interface.
2. Works on all modern browsers.
3. Backwards Compatibility.
4. Very simple configuration.
5. Support all the theme.
6. SEO compatible.
7. WP-SEO-Paginate can also be used to paginate post comments

Translations: http://plugins.svn.wordpress.org/wp-seo-paginate/trunk/I18n (check the version number for the correct file)
	
== Installation ==

*Install and Activate*

1. Unzip the downloaded WP-SEO-Paginate zip file
2. Upload the `wp-seo-paginate` folder and its contents into the `wp-content/plugins/` directory of your WordPress installation
3. Activate WP-SEO-Paginate from Plugins page

*Implement*

For posts pagination:
1) Open the theme files where you'd like pagination to be used. Usually this is the `loop.php` file. For older version of WordPress, you may need to update the `index.php`, `archive.php` and `search.php` files.

2) Replace your existing `previous_posts_link()` and `next_posts_link()` code block with the following:

	<?php if(function_exists('wp_paginate')) {
		wp_paginate();
	} ?>


For comments pagination:
1) Open the theme file(s) where you'd like comments pagination to be used. Usually this is the `comments.php` file.

2) Replace your existing `previous_comments_link()` and `next_comments_link()` code block with the following:

	<?php if(function_exists('wp_paginate_comments')) {
		wp_paginate_comments();
	} ?>


*Configure*

1) Configure the WP-SEO-Paginate settings, if necessary, from the WP-SEO-Paginate option in the Settings menu

2) The styles can be changed with the following methods:

* Add a `wp-seo-paginate.css` file in your theme's directory and place your custom CSS there
* Add your custom CSS to your theme's `styles.css`
* Modify the `wp-seo-paginate.css` file in the wp-seo-paginate plugin directory

*Note:* The first two options will ensure that WP-SEO-Paginate updates will not overwrite your custom styles.

== Frequently Asked Questions ==
You can Check FAQ on my website :<br />
[WP-SEO-Paginate](http://onlinewebapplication.com/2011/10/wp-seo-paginate.html)<br />


== Screenshots ==

You can Check Screen Shots on my website :<br />
[WP-SEO-Paginate](http://onlinewebapplication.com/2011/10/wp-seo-paginate.html)<br />

== Changelog ==
= 2.2 =
* Compatible with WordPress 3.8.

= 2.1 =
* Compatible with WordPress 3.4.1.

= 2.0 =
* Initial release

== Upgrade Notice ==
= 2.2 =
Compatible with WordPress 3.8.

= 2.1 =
Compatible with WordPress 3.4.1.

