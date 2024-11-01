=== Plugin Name ===
Contributors: Tim Heuer
Tags: silverlight, microsoft, tim heuer, wpf
Requires at least: 2.8.0
Tested up to: 2.8.5
Stable tag: 1.0.5

Silverlight Audio Player for WordPress allows a WordPress user to specify an audio file to be played back using the Silverlight Audio Player from Mark Heath (http://slaudioplayer.codeplex.com).

== Description ==

Microsoft Silverlight is a browser plugin for enabling rich internet and media applications.  This plugin makes it easy for WordPress content authors
to add audio files to their blog posts and/or pages using a simple command to specify the location of the audio file and creates a Silverlight player.

Special contributor note:
This plugin is not possible without the work of Mark Heath in creating the actual player that is used in the player.  Mark's project and source code can be found at http://slaudioplayer.codeplex.com.

== Installation ==

1. Extract all files and copy it to your plugins directory (/wp-content/plugins/).
2. Login to Wordpress Admin and activate the plugin.

A silverlight application can be embedded in a post using a tag of the following form:

[slaudio: URL]

e.g. [slaudio: http://mysite.com/media/song.mp3]

You can also override the default dimensions:

[slaudio: URL, ARTIST, TITLE]

e.g. [slaudio: http://mysite.com/media/song.mp3, Black Sabbath, Iron Man]

== Frequently Asked Questions ==

= Does this work with Silverlight 1.0 applications? =

No, this currently works with Silverlight 2+ applications that use the XAP packaging model.

== Screenshots ==
1. Player when initially viewed (collapsed)
2. Player when played (expanded with artist/title optional parameters)

== Changelog ==

= 1.0.4 =
* First real initial release of plugin

= 1.0.5 =
* Fixed screenshots

== Support ==
For support visit http://timheuer.com/silverlight-audio-for-wordpress or contact Tim directly at tim@timheuer.com.