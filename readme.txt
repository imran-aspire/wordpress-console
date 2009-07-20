=== WordPress Console ===
Contributors: sant0sk1
Donate link: http://jerodsanto.net
Tags: admin, development, ajax, interactive, developer, shell, console
Requires at least: 2.8
Tested up to: 2.8.2
Stable tag: trunk

An interactive console for WordPress developers

== Description ==

This plugin adds a "Console" page to the administrator's Tools menu which provides a JavaScript-based interactive console that loads the WordPress environment. It allows execution of arbitrary PHP code as well as anything defined by WordPress or activated plugins. This is awesome for plugin developers and people learning PHP and/or the WordPress API. Still not convinced? [Watch a screencast!](http://vimeo.com/5300607)

= New In This Version =

1.  WordPress 2.8.1 Compatibility
2.  Bug fix: move cursor to end of input on "up-arrow"
3.  Bug fix: don't allow history buffer to go negative

**SECURITY NOTICE**

This plugin is for *development*. Do NOT run this plugin on your production server unless you don't mind possibly being owned by strangers.

== Installation ==

1.  Upload wordpress-console/ directory to the wp-content/plugins directory.
2.  Activate WordPress Console through the 'Plugins' menu in WordPress.
3.  Browse to 'Tools' -> 'Console' and have at it.

== Frequently Asked Questions ==

= Who is this plugin for? =

The WordPress Console was designed to help plugin *developers* be more productive. It will do no good for the average joe user. It can also be used as a learning tool, because it provides an environment where people can play with PHP and WordPress.

= Does this plugin rock? =

Yes, yes it does.

= I want feature [X] =

You should fork the project on [GitHub](http://github.com/sant0sk1/wordpress-console) and help add it! Or contact me via [Twitter](http://twitter.com/sant0sk1) or my [blog](http://blog.jerodsanto.net) and let me know what features you think I should add.

== Screenshots ==

1.  The WordPress Console
2.  Tab Completion Example

== Changelog ==

= 0.2.1 =
* WordPress 2.8.1 Compatibility
* Bug fix: move cursor to end of input on "up-arrow"
* Bug fix: don't allow history buffer to go negative

= 0.2.0 =
* Tab-completion
* Bug fixes

= 0.1.2 =
* Bug Fix: WP installs not in root directory should get to play too.

= 0.1.1 =
* Require shared secret

= 0.1.0 =
* Initial release

== Contributors ==
* [apokalyptik](http://blog.apokalyptik.com/)
* [Doug Neiner](http://pixelgraphics.us/)