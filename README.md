=== csstimeline ===
Contributors: poetaster
Tags: shortcode,simple,style
Requires at least: 3.6
Tested up to: 4.8
Stable tag: 1.0
License: GPL
License URI: LICENSE

== Installation == 

Download into wordpress plugins directory. Enable in wordpress plugins interface. That's it.

== Frequently Asked Questions == 

None Yet.

== Changelog == 

1.0.3 - 2017.06.09  Update : tested with 4.7 and 4.8 releases.
1.0.2 - 2016.08.24 Update : css fixes, as reported in: https://wordpress.org/support/topic/css-boxes-overflowing?replies=4
1.0.1 - css fixes, initial mobile view removed (works down to 480 px)
1.0 - initial release

== Upgrade Notice == 

None yet.

== Screenshots == 

csstimeline-1.png
csstimeline-2.png

== Description ==

= EN: =

A simple wordpress plugin to parse shortcodes and produce a nice html/css only timeline.

This plugin provides 4 shortcodes:

* [ctimeline] - a wrapper for the entire timeline
* [ctentry] - a date label with an entry and option content
* [ctspace] - a simple spacer
* [ctdate] - not implemented yet.

An  example

[ctimeline]

[ctentry date="" label="<b>2015</b>"] Wasn't much going on in 2015.[/ctentry]

[ctentry date="11 May 2015 " label="The title of this entry reflects the needs of verbose headline copy editors."]
<img src="https://netzpolitik.org/wp-upload/house-of-parliament-westminster-150x150.jpg" alt="Das britische Parlament" width="150" height="150" class="alignnone size-thumbnail wp-image-112853" />
amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
[/ctentry]

[ctspace][/ctspace]

[ctspace][/ctspace]

[ctentry date="" label="<b>2016</b>"] A bit more going on in 2016.[/ctentry]

[ctentry date="12 May 2016" label="12th cool"]
Curabitur tortor. Pellentesque nibh. Aenean quam. In scelerisque sem at dolor. Maecenas mattis. Sed convallis tristique sem. Proin ut ligula vel nunc egestas porttitor. Morbi lectus risus, iaculis vel, suscipit quis, luctus non, massa. Fusce ac turpis quis ligula lacinia aliquet. Mauris ipsum. Nulla metus metus, ullamcorper vel, tincidunt sed, euismod in, nibh. Quisque volutpat condimentum velit. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Nam nec ante.
[/ctentry]

[ctentry date="13 May 2016" label="13th cool"]
In scelerisque sem at dolor. Maecenas mattis. Sed convallis tristique sem. Proin ut ligula vel nunc egestas porttitor. Morbi lectus risus, iaculis vel, suscipit quis, luctus non, massa. Fusce ac turpis quis ligula lacinia aliquet. Mauris ipsum. Nulla metus metus, ullamcorper vel, tincidunt sed, euismod in, nibh. Quisque volutpat condimentum velit. Curabitur tortor. Pellentesque nibh. Aenean quam. In scelerisque sem at dolor. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Nam nec ante. Curabitur tortor. Pellentesque nibh. Aenean quam. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
[/ctentry]

[/ctimeline]
