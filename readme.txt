=== Free Downloads - WooCommerce Premium ===
Contributors: squareonemedia, rwebster85
Author URI: https://www.squareonemedia.co.uk
Plugin URL: https://squareonemedia.co.uk/products/free-downloads-woocommerce/
Requires at Least: 4.4
Tested up to: 4.8.2
Stable tag: trunk
License: GPLv2
License URI: https://www.gnu.org/licenses/gpl-2.0.html
Tags: woocommerce, downloads, downloadable, free downloads, download now, download no checkout, download button, download now button, wordpress, e-commerce, ecommerce

Allow users to instantly download your free digital products without going through the checkout.

== Description ==

**Free Downloads** is the definitive plugin for offering free downloads on your WooCommerce store. It allows users to bypass the checkout to download your free products, supports single and multiple files, and is highly customisable. You can also see how many times your products have been downloaded for free.

This plugin has been designed for content creators and distributors to fully take advantage of their digital store. Whether you sell audio files, course documentation, themes and plugins, or just want to offer digital catalogues for your tangible products, this plugins allows your visitors to get to your free downloads with ease.

This plugin is safe and rock-solid secure, and everything is handled by your server including authentication, so you don't have to worry.

**Free Downloads** is also fully integrated with the official **Memberships** and **Subscriptions** plugins for WooCommerce.

= How it works =

By default any downloadable products that are free will be affected by this plugin. There is an option in the plugin settings if you would like to include paid items that are on sale for free, by default they aren't.

However, the plugin works right out of the box as it should, and only requires customising if you want to.

Rather than the *Add to Cart* button showing on product pages, site visitors will be presented with a download button, or for multiple files on a single product a set of links to each individual file will show. You can customise the experience for your visitors with several display options from links, to buttons, and even checkboxes. Once clicked the file will be securely downloaded automatically. For multiple files, the plugin dynamically creates a zip file that includes all the files for that product, and downloads that instead.

= Customisation =

The plugin can be customised in several ways including how the download buttons or links are presented, their appearance, should users be logged in, and more. Check out the plugin settings page for everything.

= Support =

Full supporting documentation is included with the plugin, available on the plugin settings page. There's a user guide, explanation of every setting, and FAQ with support forum links.

== Installation ==

**Manually in WordPress**

1. Download the plugin ZIP file from WordPress.org
2. From the WordPress admin dashboard go to Plugins, Add New
3. Click Upload Plugin, locate the file, upload
4. In the WordPress dashboard go to Plugins, Installed Plugins, and activate **Free Downloads**

**Manually using FTP**

1. Download the plugin ZIP file, extract it
2. FTP to your server and go to your root WordPress directory
3. Navigate to wp-content/plugins
4. Upload the parent directory *download-now-for-woocommerce* - the folder that contains the file som-woocommerce-download-now.php - to that location
5. In the WordPress dashboard go to Plugins, Installed Plugins, and activate **Free Downloads**

You can customise **Free Downloads** on the Plugins, Free Downloads dashboard page.

== Frequently Asked Questions ==

= What version of WooCommerce is supported? =

**Free Downloads** only supports WooCommerce version 3.0 and above.

= How can I get support? =

**Free Downloads** comes complete with a full guide and explanation of the plugin settings. These are available on the plugin settings page. If you need more help, please feel free to post in the [support forum](https://wordpress.org/support/plugin/download-now-for-woocommerce/).

= How are files downloaded? =

The short answer is the plugin uses a safe and secure form on the front-end which requests the file. A second round of security checks is performed, and if everything is ok the file is downloaded using the WooCommerce downloader; as well as using the download method you set for WooCommerce **(Force Downloads, X-Accel-Redirect/X-Sendfile, or Redirect)**.

= How are the dynamically created ZIP files handled? =

The product files must have been uploaded to your WordPress site, for example using the WooCommerce **Choose File** option, otherwise the ZIP file will be empty. They will not be included if they are external links.

Once created with either all of the files for a product or a selection of the files, it is temporarily saved in a folder on your server. Every hour that folder is emptied. If you deactivate this plugin, that folder and its contents will be removed.

If you use external file links it is recommended that you use the **Links Only** display method, if you have products with multiple files.

= Are the full links to files visible to a user? =

That depends on your WooCommerce settings.

If you use the **Force Downloads** or **X-Accel-Redirect/X-Sendfile** download methods (found in the WooCommerce settings, Products, Downloadable Products) for your store downloading, the file paths and URLs will be hidden. If there are multiple files downloaded as a dynamically created ZIP file, regardless of setting, the URLs will be hidden.

If you use the **Redirect** download method, the full URL may be visible for single files. For example, a PDF. This is the same as it would be without this plugin.

If in doubt and you're worried test it yourself on your own site, or please don't hesitate to [get in touch](https://wordpress.org/support/plugin/download-now-for-woocommerce/).

= Are WooCommerce Memberships and/or Subscriptions supported? =

Yes, implicitly. The official Memberships and Subscriptions plugins from Woo are supported. If you have a free product that requires a user have a membership to purchase, that free product will only be available to download if the user is a member.

= What other plugins are supported? =

**Free Downloads** should be compatible with most plugins. If you have a problem please get in touch and we will include support if possible.

Below is a list of explicitly supported plugins:

* TI WooCommerce Wishlist

== Screenshots ==

1. Product with single file (version 2.0)
2. Button with custom text (version 2.0)
3. Multiple files (with optional checkboxes) (version 2.0)
4. One of the settings screens (version 2.0)
5. Support page (version 2.0)
6. Download counts (version 2.2)

== Changelog ==

= 2.4.95 - 15/12/2017 =
* Included POT file. Plugin should now be translation ready.

= 2.4.94 - 15/12/2017 =
* Preparation for plugin internationalisation

= 2.4.93 - 12/12/2017 =
* New Option: Force ZIP file creation for single files

= 2.4.92 - 21/11/2017 =
* Fixed bug on user account memberships page
* Download buttond now add/remove a "loading" class when clicked
* General housekeeping

= 2.4.91 - 18/10/2017 =
* Removed outdated get_product() function calls, replaced with wc_get_product()

= 2.4.9 - 16/10/2017 =
* Fixed compatibility for WooCommerce Memberships 1.9+

= 2.4.8 - 10/10/2017 =
* Fixed bug with "Links Only" multiple file download option

= 2.4.7 - 09/10/2017 =
* Changed download form actions to make plugin more compatible with security features found in some plugins/themes

= 2.4.6 - 03/10/2017 =
* Fixed bug with displaying button text on shop pages

= 2.4.5 - 01/10/2017 =
* Renamed plugin to Free Downloads - WooCommerce
* New Option: add custom CSS classes to the download buttons and links
* Error message now displays if "download all" zip file is empty, usually caused by using external links
* General housekeeping

= 2.4.4 - 12/04/2017 =
* Changes for compatibility with WooCommerce version 3.0+
* Plugin now only supports WooCommerce version 3.0 and above

= 2.4.3 - 16/03/2017 =
* Fixed error when user has no memberships in the membership site

= 2.4.2 =
* Now supports WooCommerce Memberships version 1.7+

= 2.4.1 =
* Fixed bug where Membership download would fail on some setups

= 2.4 =
* Membership items with a 100% discount for members can now be included. This option is off by default

= 2.3.82 =
* Change to hide cart CSS logic

= 2.3.81 =
* Fixed plugin activation error

= 2.3.8 =
* Ouput CSS to hide the cart when download button shows, to support more plugins that may conflict.
* Added new actions to plugin activation and deactivation

= 2.3.7 =
* Fixed detection of WooCommerce Memberships on some setups

= 2.3.6 =
* WooCommerce Memberships - New settings for extra customisation
* Rewritten some functions as actions and filters
* Changed hard-coded front-end text strings to translatable functions
* General housekeeping

= 2.3.5 =
* Plugin settings now feature as an admin menu section, not plugin menu
* New feature: reset product free download count
* Code changes to use of wp_upload_dir() to fix rare PHP error

= 2.3.4 =
* Fixed bug in 2.3.3

= 2.3.3 =
* 2 new shortcodes added, one to display a free download link and another to display the free download cart content like a single product page.
* General housekeeping

= 2.3.2 =
* Fixed bug when using the [product_page id=""] WooCommerce shortcode
* Changed archive page output to anchor links instead of buttons
* General housekeeping

= 2.3.1 =
* Minor change to script loading to correct rare PHP error

= 2.3 =
* New Option: Allow download from shop / archive pages
* Added the before/after form/button WooCommerce hooks to the download buttons
* Fixed bug introduced in version 2.2 preventing download when using links
* Fixed variations being properly excluded

= 2.2 =
* Download counts now visible on products page columns (admin area)
* New support section called Features

= 2.1 =
* PDF Viewer feature. PDF files will be previewed instead of downloaded (optional)
* Individual products can now be selected, instead of globally affecting all
* Free download count now included on each product page
* General housekeeping

= 2.0 =
* Rebuilt from the ground up to be better than ever before
* Overhauled download procedure, now uses secure WooCommerce download methods
* File paths are hidden, everything is handled securely by the server
* New options pages for a tonne of customisations
* Now supports WooCommerce Memberships and Subscriptions
* Fully supports products with multiple files, several display options available
* Multiple files are wrapped up in a dynamically created ZIP file, and downloaded instantly
* Full supporting documentation built right into the plugin

= 1.11 =
* No longer conflicts with variations

= 1.1 =
* Bug fixes

= 1.0 =
* Initial release
