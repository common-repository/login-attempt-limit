=== Limit Login Attempts ===
Contributors: themeegg
Tags: login, authentication, security
Requires at least: 2.8
Tested up to: 4.9.1
Stable tag: 1.0

Limit rate of login attempts

== Description ==

Limit the number of login attempts possible both through normal login as well as using auth cookies.

By default WordPress allows unlimited login attempts either through the login page or by sending special cookies. This allows passwords (or hashes) to be brute-force cracked with relative ease.

Limit Login Attempts blocks an Internet address from making further attempts after a specified limit on retries is reached, making a brute-force attack difficult or impossible.

Features
* Limit the number of retry attempts when logging in (for each IP). Fully customizable
* Limit the number of attempts to log in using auth cookies in same way
* Informs user about remaining retries or lockout time on login page
* Optional logging, optional email notification
* Handles server behind reverse proxy
* It is possible to whitelist IPs using a filter. But you probably shouldn't. :-)

== Installation ==

1. Upload the entire login-attempt-limit folder to the /wp-content/plugins/ directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. In your Widgets menu, simply drag the widget labeled "Login Attempt Limit" into a widget area.
4. Configure the it's setting from tools => Limit Login Attempts

Please visit our official page for <a href="http://docs.themeegg.com/docs/login-attempt-limit/" target="_blank">Documentation and more information</a>.

Get free support at http://themeegg.com/support-forum/

== Frequently Asked Questions ==

= What is the plugin license? =

* This plugin is released under a GPL license.

= Does the plugin work with any WordPress themes?

Yes, the plugin is designed to work with any themes that have been coded following WordPress guidelines.

= I would like to contribute, do you have any option for that ?

Yes, You can contribute to this plugin to make more awesome on Github [Login Attempt Limit](https://github.com/themeegg/login-attempt-limit)

== Screenshots ==


== Changelog ==
= 1.0 =
* Initial released