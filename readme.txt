=== Theme Tweaker ===
Contributors: manojtd
Donate link: http://www.Thulasidas.com/buy
Tags: theme, colors, admin, css, tweak
Requires at least: 2.5
Tested up to: 3.2
Stable tag: 2.00

Theme Tweaker lets you modify the colors in your theme with no CSS/PHP editing.

== Description ==

*Theme Tweaker* displays the existing colors from your current theme, and gives you a color picker to replace them. It also lets you change them in bulk, like invert all colors, use grey scale etc.

Furthermore, *Theme Tweaker* allows you to preview or activate your changes. Finally, you can save the modified stylesheet locally and upload it into your blog server to deploy your new color scheme.

*Theme Tweaker* will now generate a fully functional child theme for you! Using child themes, you leave your original (parent) theme untouched, so that it can be updated independently without losing your tweaks.

Cannot complete the tweaking in one sitting? No problem, *Theme Tweaker* lets you save your work and pick it up from here you leave off. Moreover, *Theme Tweaker* will remember your saved color schemes for any number of themes.

If you like *Theme Tweaker*, you may want to check out my other plugins: [Easy AdSenser](http://wordpress.org/extend/plugins/easy-adsenser/ "The simplest way to put AdSense to work for you") and [Easy LaTeX](http://wordpress.org/extend/plugins/easy-latex/ "To display mathematical equations in your blog using LaTeX").

== Upgrade Notice == 

= 1.72 =

Minor bug fixes

== Screenshots ==

1. How to tweak your theme using *Theme Tweaker*.
2. *Theme Tweaker* in action - on my own blog. Before tweaking.
3. *Theme Tweaker* in action - on my own blog. After tweaking to inverted colors.

== Installation ==

1. Upload the *Theme Tweaker* plugin (the whole theme-tweaker folder) to the '/wp-content/plugins/' directory.
2. Activate the plugin through the 'Plugins' page in WordPress.
3. Go to the Design -> Theme Tweaker and start tweaking your theme colors!
4. Or, use the "Settings" link in the Plugins page next to *Theme Tweaker* to reach the tweaking paradise.

== Frequently Asked Questions ==

= Great idea, but doesn't work with my theme. What gives? =

This plugin works as follows: It first identifies the strings in the `style.css` file of your theme that look like colors. It them presents them to you with an option to replace them using a color-picker. The replaced colors are dynamically inserted in the header of your pages as they are generated. 

This scheme worked great when I first developed. But now, more and more themes (especially the ones that offer you a color-picker) are using the same strategy to control the appearance of your pages. They keep the color definitions in places other than the `style.css` file such as their `php` files, and the database. Such schemes will foil the color tweaking strategy of this plugin. 

= How come there is not a single frequently asked question? =

Two possible reasons.

1. *Theme Tweaker* is so simple and straight-forward that no question could be thought of.
2. More likely, the plugin is too new for any questions.

= I need your help =

*Theme Tweaker* has an option to convert your color scheme to grey scale. The algorithm used is this: for a color rgb = (r,g,b), find y = 0.3r + 0.59g + 0.11b, grey = rgb(y,y,y).
I am thinking of other color tweaking options such as increase/decrease contrast or brightness, convert to sepia and so on. If you have the algorithms for such conversions, would you like to post them?

= How do I report a bug or ask a question? =

Please report any problems, and share your thoughts and comments [at the plugin forum at WordPress](http://wordpress.org/tags/theme-tweaker "Post comments/suggestions/bugs on the WordPress.org forum. [Requires login/registration]") Or send an [email to the plugin author](http://manoj.thulasidas.com/mail.shtml "Email the author").

== Change Log ==

* V2.00: Verifying compatability up to WP3.2. Changes in the documentation. [June 22, 2011]
* V1.71: Fixing the problem of the theme stylesheet overwriting the tweaked colors. [August 14, 2009]
* V1.70: Changed stylesheet saving methods to something simpler and more elegant. [July 14, 2009]
* V1.63: Generate random colors locally using JavaScript. [May 8, 2009]
* V1.62: New option to launch a preview window from the Theme Tweaker interface. [Apr 28, 2009]
* V1.61: Further improvements of the admin menu interface to make it XHTML transitional 1.0 valid (according to W2C). [Apr 19, 2009]
* V1.60: Major overhaul of the interface. New clean look with javascript tooltips. New options to clean up the database entries. [Apr 12, 2009]
* V1.50: Option to suppress the credit link "Theme Tweaker by Unreal". [Apr 5, 2009]
* V1.43: Documentation and interface improvements only. [Feb 15, 2009]
* V1.42: Another good bug fix -- *Theme Tweaker* can now deal with url(image) specifications in the style.css file. [Feb 12, 2009]
* V1.41: A major bug fix -- *Theme Tweaker* now handles multi-line CSS blocks properly. [Feb 11, 2009]
* V1.40: Child theme generation. [Jan 30, 2009]
* V1.30: New bulk action -- Randomize Colors. [Jan 7, 2009]
* V1.23: Added title attribute on color patches. [Jan 1, 2009]
* V1.22: Added Sepia option. [Dec 26, 2008]
* V1.21: Easier link in the Plugins page, better documentation. [Dec 17, 2008]
* V1.20: Optimized the generated CSS to minimize its size. Tested with WordPress 2.7. [Dec 13, 2008]
* V1.12: Fixed the conflict between WordPress theme preview and theme-tweaker. Eliminated the limitation of button/background bitmaps being ignored. [Dec 8, 2008]
* V1.11: Fixed a stupid bug (forgot to remove test code, sorry).
* V1.10: Added the ability to save the tweaked color scheme to a stylesheet for uploading. Used WordPress stylesheets for better look and feel integration in the blog admin pages.
* V1.00: Initial release. [Dec 5, 2008]

== Limitations ==

1. *Theme Tweaker* works only on the colors found in the theme stylesheet. If you have plugins that introduce their own color schemes, they are not tweaked.
2. Images (especially background images and transparent GIFs) may not match your new color scheme (which is more of a design preference rather than a limitation the plugin).
3. *Theme Tweaker* handles only standard color specifications (#rgb, #rrggbb or the 16 colors W3C colors -- Aqua, Black, Blue, Fuchsia, Gray, Green, Lime, Maroon, Navy, Olive, Purple, Red, Silver, Teal, White, Yellow). It does not (yet) handle the rare RGB(r,g,b) or fancier color mnemonic specification in stylesheets.
4. *Theme Tweaker* may have trouble with some multi-line descriptions in style.css (rare).

== Credit ==

* *Theme Tweaker* uses the excellent Javascript color picker by [JSColor](http://jscolor.com "Javascript color picker").