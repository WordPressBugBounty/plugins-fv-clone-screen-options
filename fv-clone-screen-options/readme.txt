=== FV Clone Screen Options ===
Contributors: FolioVision
Tags: screen,screen options,editor
Requires at least: 2.7
Tested up to: 6.3
Stable tag: trunk

Simple plugin which lets you manage Screen Options of all the users on your blog.

== Description ==

Simple plugin which lets you manage Screen Options of all the users on your blog.

First set your own Screen Options and then **clone them across all users** with our plugin.

A huge time saver. Enjoy!

Note: Multisite is not supported very well, plugin doesn't distinguish between individual blogs.

[Free support available on our forums](https://foliovision.com/support/fv-clone-screen-options/)

== Changelog ==

= Version 0.4 - 2019/06/12 =
* Fix for WordPress 5.2.1 user registrations

= Version 0.3 - 2018/05/14 =
* Performance fix - properly detecting editor user roles rather than just skipping all subscribers

= Version 0.2.5 - 2017/07/03 =
* Hotfix for Multisite - plugin was adding unnecessary usermeta for all new users, regardless of user role.

= Version 0.2.4 - 2016/05/16 =
* Fix for sites with thousands of users

= Version 0.2.3 - 2016/03/01 =
* Fix for PHP warnings caused by new WordPress version.

= Version 0.2.2 - 2010/07/11 =
* Added support of WP 3.0 post types
* Added support for link and media manager
* Added sepparate button for just saving the settings for new users

= Version 0.2.1 - 2010/06/17 =
* Added support for list of posts and pages (Post -> Edit and Pages -> Edit)

= Version 0.2 - 2010/02/26 =
* Custom Screen Options configuration interface was removed.
* All the standard Wordpress Screen Options configuration panels are used, so plugin is easier to use.
* Works with post, page and dashboard screens.

= Version 0.1 - 2010/02/10 =
* Plugin has its own interface for configuring Screen Options.
* Support only for post screen.

== Upgrade Notice ==

= 0.2.2 =
Added support for Wordpress 3.0 post types.

== Frequently Asked Questions ==

= What screens are being cloned? =

For all the post types (including 'link', 'dashboard' and custom post types):

* Metabox visibility, position and open/closed state.
* Number of columns on editing screen.
* Number of items per page.
* Columns in the list of the items.

Also:

* WP admin panel menu open/closed state.
* Dashboard items.

= What user meta values are being cloned? =

Here's a list of the basic and legacy items:

* wp_user-settings
* managelink-managercolumnshidden
* manageuploadcolumnshidden
* edit_per_page
* manageeditcolumnshidden
* wp_usersettings
* edit_pages_per_page
* manageeditpagescolumnshidden
* wp_metaboxorder_post
* wp_metaboxorder_page
* wp_metaboxorder_dashboard

Also all of this for all the posts types (post, page, attachment, revision) plus 'link', 'dashboard' and all the custom post types:

* metaboxhidden_TYPE
* closedpostboxes_TYPE
* screen_layout_TYPE
* meta-box-order_TYPE
* edit_TYPE_per_page
* manageedit-TYPEcolumnshidden

== Installation ==

You can use the built in installer and upgrader, or you can install the plugin
manually.

== Screenshots ==

1. FV Clone Screen Options in your Wordpress menu
2. FV Clone Screen Options screen
3. Here's how you set your own Screen Options which you are able to clone to other users

== Testing ==

1. Go to classic editor

1.2. Change visibility of some metaboxes

1.3. Go to Tools -> FV Clone Screen Options

1.4. Click on "Clone"

1.5. Go to another user and check if the metaboxes are hidden

1.6. Create new user

1.7. Check if the metaboxes are hidden