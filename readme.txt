=== Tractis Certified Profiles ===
Contributors: Tractis
Donate link: https://www.tractis.com/
Tags: certified profiles comments security
Requires at least: 2.0.2
Tested up to: 2.8
Stable tag: 0.9

Allow your users to proof their real identity in your blog using their electronic ID, and they will show a certified profile in their comments.

== Description ==

Allow your users to proof their real identity in your blog. Your users will be able to identify in your blog using their electronic ID and they will show a certified profile in their comments.

== Installation ==

### Upload and Install
1. Upload the installation zip file to /path/to/your/blog/wp-content/plugins
1. Unzip the file
1. Go to Admin Area and click on Plugins
1. Find the plugin named Tractis Certified Profiles and click on _Activate_
1. Now you will see the plugin on the list of Currently Active Plugins.

### Configure the plugin and get your api key
1. Click on _Settings_ from the list of Currently Active Plugins.
1. The first things you need is obtain a Tractis API Key, click on _Obtain your API Key on Tractis_ link.
1. Follow the steps and copy the API Key
1. Insert it in the Tractis API Key textbox
1. Select the button that you want

### Integrate the plugin in your Wordpress theme
You have two ways of integrate the Tractis button to authenticate the users using electronic ID:

*Using the integrated Widget if your Theme supports it*

* In the admin section, go to Appearance/Widgets
* Click _Add_ on Tractis Certified Profiles
* Save the changes

*Insert the next code inside your template*

* In the theme editor go to the template that you want to show the button
* Insert the next code: `<?php widget_TractisAuth(); ?>;`

### Requeriments
You need php_openssl module working on your php installation in order to comunicate with tractis services in https.

== Frequently Asked Questions ==

= I activated the plugin and nothings happen =

You need to integrate the plugin in your theme, see the installation instructions.

= When Tractis return to my blog I see lot of php errors like this: Warning: fsockopen() [function.fsockopen]: unable to connect to ssl://www.tractis.com:443 (Unable to find the socket transport "ssl" - did you forget to enable it when you configured PHP?) =

You need php_openssl module working on your php installation in order to comunicate with tractis services in https.

== Screenshots ==


== Changelog ==

= 0.8 =
* Initial release.
