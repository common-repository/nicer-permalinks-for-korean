=== Plugin Name ===
Contributors: artsilly
Donate link: http://masterkeykorea.com/nicer-permalinks-for-korean/
Tags: korean, permalink
Requires at least: 2.0
Tested up to: 3.0
Stable tag: 1.0

A simple plugin to remove encoded permalink which directly encoded from title in Korean

== Description ==

Internal WordPress engine simply creates permalink based on title. Non-latin characters are encoded based on RFC 1738(or its PHP implementation as urlencode function) and it produces long, non-readable URL look a like http://ko.wikipedia.org/wiki/%EB%AC%BC%EB%A6%AC_%EC%A3%BC%EC%86%8C_%ED%99%95%EC%9E%A5 . This encoded URL still works and can be decoded by browsers. It is very hard to read specially all the stats uses URL as a key. To prevent this, simply change the suggested permalink all the time or uses digit form like /?p=123.
But if you want not to be bothered, this plugin can be a solution for Roman presentation as Korean pronounciation.

Based on code of the np4v(Vietnameses version of this plugin) from Quang Anh Do. Korean-Roman presentation table is adopted from http://xpg.in/tcm/thread.php?topic_id=771. Thanks bhleejw.

For Korean explanation about this plugin or any suggestion, please visit http://masterkeykorea.com/nicer-permalinks-for-korean

== Installation ==

1. Upload `np4k/` plugin folder which has np4k.php to the `/wp-content/plugins/` directory
1. Or simply install through WordPress 'Plugins' menu
1. Activate the plugin through the 'Plugins' menu in WordPress

More Info: [Click here to read my blog post](Plugin URI: http://masterkeykorea.com/nicer-permalinks-for-korean)

== Changelog ==
= 1.0 =
* First release.
