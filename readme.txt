=== Insert or Embed iSpring Content into Wordpress ====
Contributors: elearningplugins.com
Donate link: http://www.elearningplugins.com
Tags: iSpring, insert, embed, iframe, elearning
Requires at least: 2.0.2
Tested up to: 4.7
Stable tag: 1.1
Quickly embed or insert iSpring content into a post or page

== Description ==

This plugin will add a new toolbar icon (the iSpring logo) next to the 'Add Media' button on the Edit Post and Edit Page pages.  Upon clicking this toolbar icon, you will have the ability to upload your published iSpring content as a ZIP file.  Once uploaded, the plugin will automatically extract the content, find the appropriate .html file, and add code to your post or page that will display your iSpring content as an iframe or a lightbox.

https://www.youtube.com/watch?v=OW73OvgLaWI

== Installation ==

1. Upload the 'insert-or-embed-ispring-into-wordpress' folder to the `/wp-content/plugins/` directory. Activate the plugin through the 'Plugins' menu in WordPress

== How to Use ==

Check out the screencast in the link below to learn how to use this plugin: https://www.youtube.com/watch?v=OW73OvgLaWI

== Frequently Asked Questions ==

= How do I use this to embed iSpring content? =

Check out this screencast:  https://www.youtube.com/watch?v=OW73OvgLaWI

= Does this work with iSpring Presenter and QuizMaker content? =

Yes, it works with all iSpring output.

= How do I increase the maximum upload file size? = 

The maximum upload file size is determined by your hosting provider, not a limit enforced by the WordPress plugin. To increase the limit, you need to update your php.ini file in your wp-admin folder to reflect the following:

post_max_size = 150M

max_execution_time = 60

max_input_time = 60

upload_max_filesize = 150M


(These settings will vary depending upon your server and content. You may need to contact your hosting company to make these changes.

= Why does the upload never finish or I get a -1 error message? =

In order to resolve this issue, you need to update your php.ini in your wp-admin folder to reflect the following: 

post_max_size = 150M

max_execution_time = 60

max_input_time = 60

upload_max_filesize = 150M


(These settings will vary depending upon your server and content.  You may need to contact your hosting company to make these changes.) 

= If I delete the plugin, what happens to the content that I've uploaded? =

The uploaded content is saved into the wp-content / uploads / ispring_uploads folder on your site.  Thus, your uploaded content will not be removed if you delete this plugin.

== Upgrade Notice ==

Fixed issue where the second page of content in the content library would be blank.

== Changelog ==

= 1.1 =

Fixed issue where the second page of content in the content library would be blank.

= 1.0 =

Initial version.