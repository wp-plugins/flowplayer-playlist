=== Flowplayer Playlist ===

Contributors: eye8
Donate link: 
Tags: video, Flowplayer, playlist
Requires at least: 3.2
Tested up to: 3.5.1
Stable tag: 0.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Flowplayer Playlist is a free plugin to embed video playlist in WordPress.

== Description ==

Flowplayer Playlist is a free plugin to embed video playlist in WordPress.

* Uses the open-source web video player Flowplayer (latest Flash-based version). Flowplayer package is upgradable when a new version is available.
* Supports FLV, MP4, and F4V video formats (all those supported by Flowplayer).
* Provide your Flowlayer license to use the Flowplayer commercial version. If no license key is provided, it will use the free version bearing the Flowplayer trademark.
* Flowplayer license supports multisite. Subdomains automatically inherit the license key from the main blog (if any). License key specified in the subdomain will overwrite the key from the main blog, allowing flexibility in larger WordPress blog network.

Right now you have to upload your videos to somewhere over the web with public access (e.g. the 'Public' folder in your Dropbox account) and use the public URLs to embed. But I am considering future features such as integrating the media library in WordPress or a Content Delivery Network (CDN) such as Dropbox or Box.net. Some other features in consideration:

* More Flowplayer configuration parameters such as background color, controlbar color, splash image, custom branding.
* Supports Youtube videos using the Youtube Player API.
* Advertisement mode (repeated playback without controlbar).

Please make feature requests in the support section. I will decide which ones to implement first based the feedback.

== Installation ==

1. Upload the plugin package 'flplaylist' to the `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in Wordpress. A menu item called FlPlaylist will show up in the left menu.
3. Go to menu FlPlaylist->Add New, provide a title, choose a few options, and add one or more web video URLs to create a video playlist.
4. Publish the playlist. 
5. Use the shortcode beneath the Video URLs textbox in your post or page to embed the playlist.

== Frequently asked questions ==

= Where do I upload my videos? =

In v.0.1 you have to find your own content delivery service in order to use this plugin. A suggested service is Dropbox (free or paid) where you can upload your videos in the 'Public' folder and sync them over the web. Then you can use the publicly accessible URLs that Dropbox provided in this plugin.

= Can I use audio files in the playlist? =

Sorry not right now. But if you find this is really what you need please make a feature request.

== Screenshots ==

1. https://dl.dropboxusercontent.com/u/7783459/flplaylist/screenshots/001.png
2. https://dl.dropboxusercontent.com/u/7783459/flplaylist/screenshots/002.png
3. https://dl.dropboxusercontent.com/u/7783459/flplaylist/screenshots/003.png
4. https://dl.dropboxusercontent.com/u/7783459/flplaylist/screenshots/004.png

== Changelog ==

= 0.1 =

First stable release

== Upgrade notice ==



== Arbitrary section 1 ==


