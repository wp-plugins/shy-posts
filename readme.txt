=== Plugin Name ===
Contributors: topher1kenobe
Tags: posts
Requires at least: 3.0
Tested up to: 3.6
#Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Provides a checkbox on a post admin page to allow you to say that THIS post should not appear on the homepage blog loop.

== Description ==

Provides a checkbox on a post admin page to allow you to say that THIS post should not appear on the homepage blog loop.

This only works if your blog is on your homepage.

== Installation ==

This section describes how to install the plugin and get it working.

1. Upload the `shy-posts` folder to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Create new or Edit a Post.

== Frequently Asked Questions ==

= Why don't you have more questions here? =

I haven't been asked any yet.  :)

== Screenshots ==

1. This screen shot description corresponds to screenshot-1.(png|jpg|jpeg|gif). Note that the screenshot is taken from
the /assets directory or the directory that contains the stable readme.txt (tags or trunk). Screenshots in the /assets 
directory take precedence. For example, `/assets/screenshot-1.png` would win over `/tags/4.3/screenshot-1.png` 
(or jpg, jpeg, gif).
2. This is the second screen shot

== Changelog ==

= 1.1 =
* Change pre_get_posts filter to an action
* Change $query->is_home() to is_front_page()
* remove !is_admin() check (is_front_page takes care of that)

= 1.0 =
* Initial release.
