# Exopite-Lazy-Load-XT-WordPress-Plugin
Exopite Lazy Load XT lazy load your images, videos and iframes using Ressio Lazy Load XT jQuery plugin.

- Author: Joe Szalai
- Version: 20190521
- Plugin URL: https://github.com/JoeSz/Exopite-Lazy-Load-XT-WordPress-Plugin
- Author URL: https://joe.szalai.org
- License: GNU General Public License v3 or later
- License URI: http://www.gnu.org/licenses/gpl-3.0.html

DESCRIPTION
-----------

Lazy load images to improve page load times. Page speed is important, not only for SEO but also for your customers user experience.

Exopite Lazy Load XT lazy load your images, videos and iframes using <a href="https://github.com/ressio/lazy-load-xt" target="_blank">Ressio Lazy Load XT</a> jQuery plugin.

Plugin uses <a href="http://simplehtmldom.sourceforge.net/" target="_blank" rel="noopener">PHP Simple HTML DOM Parser</a> and not REGEX to parse content.

The plugin works by replacing the src attributes with data-src and loading the Lazy Load XT script when the content or page meta is loaded on the front end of your site.

Since GoogleBOT crawling javascript, there is no disadvantage of this technique. Official news on crawling and indexing sites for the Google index.

FEATURES
--------

- Replace sepcified type of content in the_content and widget_text.
- Can be turn on/off what types of content want you to lazy load (images, videos, iframes, background images).
- Can also be exclude content between `[NOLAZY][/NOLAZY]` and tags,
- or with a specified class. Default: `.no-lazy` This is especially usefull if you are already using other lazy load based plugins/sliders, like Master Slider.
- Override placeholder images via `exopite_lazyload_xt_placeholder_image`,
- Turn off lazy loading via `exopite_lazyload_xt_enabled` filter. Can use for disable it on a specific page, etc...

Install and activate plugin. It will do the rest. Configurations are not required. You do not have to change any settings.

REQUIREMENTS
------------

Server

* WordPress 4.0+ (May work with earlier versions too)
* PHP 5.3+ (Required)
* jQuery 1.9.1+

Browsers

* Modern Browsers
* Firefox, Chrome, Safari, Opera, IE 10+
* Tested on Firefox, Chrome, Edge, IE 11

INSTALLATION
------------

1. [x] Upload `exopite-lazy-load-xt` to the `/wp-content/plugins/exopite-lazy-load-xt/` directory

OR

1. [ ] ~~Install plugin from WordPress repository (not yet)~~

2. [x] Activate the plugin through the 'Plugins' menu in WordPress

CHANGELOG
---------

= 20190521 - 2019-05-21 =
* Update: Update Exopite Simple Options Framework

= 20190213 - 2019-02-13 =
* Update PHP Simple HTML DOM Parser to 1.8.1 ensure PHP 7.3 compatibility

= 20181123 - 2018-11-23 =
* Updated: Exopite Simple Options Framework
* Updated: update URL
* Add: plugin upgrade notification

= 20180609 - 2018-06-09 =
* Updated: Exopite Simple Options Framework
* Fixed: typo button_bar field

= 20180329 - 2018-03-29 =
* Added: Update checker

= 20180121 - 2018-01-21 =
* Fixed: videos only apply to video[data-src].
* Fixed: remove lazy-hidden from videos.

= 20180101 - 2018-01-01 =
* Added: new options menu.

= 20171225 - 2017-12-25 =
* Added: option to select between methods.

= 20171224 - 2017-12-24 =
* Added: new method to process images. Process HTML with output buffering
  just before sent to browser. This is the default method.

= 20171102 - 2017-11-02 =
* Fixed: If content contains widgets (eg. Page Builders) <noscirpt> appeared twice.

= 20170921 =
* Initial release


LICENSE DETAILS
---------------
The GPL license of Sticky anything without cloning it grants you the right to use, study, share (copy), modify and (re)distribute the software, as long as these license terms are retained.

DISCLAMER
---------

NO WARRANTY OF ANY KIND! USE THIS SOFTWARES AND INFORMATIONS AT YOUR OWN RISK!
[READ DISCLAMER.TXT!](https://joe.szalai.org/disclaimer/)
License: GNU General Public License v3

[![forthebadge](http://forthebadge.com/images/badges/built-by-developers.svg)](http://forthebadge.com) [![forthebadge](http://forthebadge.com/images/badges/for-you.svg)](http://forthebadge.com)
