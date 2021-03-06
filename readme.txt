﻿=== WP-Compress-HTML ===
Author: Mandar Marathe
URL: http://www.mandar-marathe.com
Contact: info@mandar-marathe.com
Contributors: mandar-marathe
Tags: compress, html, template, space
Requires at least: 2.5
Tested up to: 3.3.1
Stable tag: trunk

Reduces the HTML file size by removing unnecessary white space from the HTML document created by the WordPress blog.

== Description ==

Coders like to use spaces, carriage returns, new lines, tabs and indentation to make their HTML documents human-readable. This helps collaboration and debugging of the HTML document. However, all these features add to the filesize of the resultant HTML document. This structural information is totally ignored by browsers.

This plugin removes spaces, carriage returns, new lines and tabs from your HTML document. You can therefore freely use these features while writing HTML, safe in the knowledge that it will not bloat the final HTML document.

With this plugin you can also mark areas of your HTML template where you want to preserve white space - for example - in areas containing Javascript which needs carriage returns and new lines to function correctly.

HTML comments are not affected by this plugin.


== Installation ==

1. Download the plugin.
2. Extract the wp_compress_html.php file and upload to the '/wp-content/plugins/' directory.
3. Activate the plugin through the 'Plugins' menu in WordPress.
4. If there are areas which you do NOT want compression to be applied, simply enclose each area with a pair of &lt;!--wp-compress-html--&gt; tags. Drop in a &lt;!--wp-compress-html no compression--&gt; tag within each area marked in this way to tell the plugin that area is not to be compressed. Don't worry - these configuration tags will be stripped out by the plugin.


== Frequently Asked Questions ==

= Why do I need this plugin? =

When you are coding your HTML template, you will almost certainly want to add spaces, tabs and carriage returns to the document. This helps you to read it, but this information is ignored by the browser and transmitting it to the browser is a waste of bandwidth. It bloats your files and slows your site down. This plugin will remove all this unnecessary "white space".

= How do I mark areas that should not be compressed? =

Look at the screenshot at http://www.mandar-marathe.com/img/wp-compress-html-screenshot2.gif to see how to mark areas in your template that should not be compressed.



= Does it work for WordPress version x.x.x? =

The plugin has been tested upto WordPress version 3.3.1.

 