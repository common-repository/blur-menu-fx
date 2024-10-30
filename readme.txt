=== Blur Menu FX ===
Contributors: flashxml
Tags: images, photos, widget, post, plugin, posts, sidebar, free, flash, menu, text, as3, effect, xml, vertical, horizontal, blur, animation, roll, over, out
Requires at least: 2.8.0
Tested up to: 3.0.1
Stable tag: trunk

A versatile free Blur Menu. Fully XML customizable without any Flash knowledge. And it's free!

== Description ==

The Blur Menu FX can be embedded in any website for free without even using Flash. The overall width and height can be customized up to 1680 x 1050 pixels. It can have vertical or horizontal orientation, supports any type of font alignment, it has customizable bevel and shadow effects and there are reflection effects for each item and roll over/out effects. There are also many other customizable properties on the Live Demo.

== Installation ==

Make sure your Wordpress version is greater than 2.8 and your hosting provider is using PHP5.

1. There are two files to download: [WordPress Plugin](http://downloads.wordpress.org/plugin/blur-menu-fx.zip "Blur Menu FX Plugin") (that you have to install and activate) & [Free archive](http://www.flashxml.net/free/download/blur-menu.zip "Blur Menu FX")
2. Create a new folder inside your **wp-content** folder called **flashxml**, inside this folder create a new one called **blur-menu-fx** and copy the content of the **free archive** there
3. If you copied the **free archive** to a location different than the one above, go to **Blur Menu FX** from the **Settings** tab in your **WordPress Dashboard** and update the path accordingly
4. Add `[blur-menu-fx][/blur-menu-fx]` where you want the Flash to show up in your post/page
5. If you want to make the Blur Menu FX part of your theme, edit the template files and add `<?php blurmenufx_echo_embed_code(); ?>` where you want it to show up
6. Go to [FlashXML.net](http://www.flashxml.net/ "Free Flash Components") and [customize your Blur Menu FX](http://www.flashxml.net/blur-menu.html "Blur Menu FX") using the Live Demo. Generate the `settings.xml` text and use it to overwrite `wp-content/flashxml/blur-menu-fx/settings.xml`

= Additional settings file =

To embed the Blur Menu FX more than once, you will need another settings file. Let's assume your new file is called `settings2.xml`. Add `[blur-menu-fx settings="settings2.xml"][/blur-menu-fx]` where you want the Flash to show up in your post/page. If you made the Flash part of your theme, add the file name as **the first argument** of the `blurmenufx_echo_embed_code()` function call (for example `<?php blurmenufx_echo_embed_code("settings2.xml"); ?>`).

= No Flash support text =

To support visitors without Adobe Flash Player, you can provide alternative content by adding the text between `[blur-menu-fx]` and `[/blur-menu-fx]`. If you made the Flash part of your theme, add the text as **the second argument** of the `blurmenufx_echo_embed_code()` function call (for example `<?php blurmenufx_echo_embed_code("","Alternative content"); ?>`).

= If you have PHP4 =

To make it work with PHP4, add `[blur-menu-fx width="600" height="300"][/blur-menu-fx]` where you want the Flash to show up in your post/page. If you made the Flash part of your theme, add the width and height as **the third and fourth argument** of the `blurmenufx_echo_embed_code()` function call. Don't forget to provide your own width and height values, since 600 and 300 are just examples.

= Getting rid of the FlashXML.net label =

To remove the FlashXML.net label from the top-left corner you'll need to buy the [paid package](http://www.flashxml.net/blur-menu.html "Blur Menu FX"). Once you'll do that, simply use the SWF file from the paid package to overwrite the SWF file from the `wp-content/flashxml/blur-menu-fx/` folder.

== Screenshots ==

1. The Live Demo on [FlashXML.net](http://www.flashxml.net/blur-menu.html "Blur Menu FX") is the utility that helps easily customize your Blur Menu FX to fit all your needs.