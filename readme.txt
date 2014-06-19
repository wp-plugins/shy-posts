=== Shy Posts ===
Contributors: topher1kenobe
Tags: posts
Requires at least: 3.0
Tested up to: 3.6.1
Stable tag: 1.3
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

1. The checkbox in the Publish box on the Post editing page

== Changelog ==

= 1.3 =
* Store shy post IDs in a transient
* Make exclusion query use transient
* New query is much MUCH faster
* Various input sanitizations

= 1.2 =
* Make the checkbox be in the Publish box instead of a custom meta box

= 1.1 =
* Change pre_get_posts filter to an action
* Change $query->is_home() to is_front_page()
* remove !is_admin() check (is_front_page takes care of that)

= 1.0 =
* Initial release.
