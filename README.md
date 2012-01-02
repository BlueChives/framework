# Introduction

The **Theme Force Framework** is the most comprehensive solution for **restaurant websites** based on WordPress. It is
structured as a **modular feature-set** highly relevant to industry needs. This read-me only provides usage instructions, please see the developer page below for more information.

## Resources

* **Must-Read** Developer Homepage: http://www.theme-force.com/framework-developers/
* GitHub Homepage: https://github.com/themeforce/framework
* Discussion & News: http://www.facebook.com/themeforce

## Requirements

In order to make use of our complete feature set, you will not require any other tools (i.e. Options Framework). This framework stands alone.

## Adding to your Theme

The contents of this framework should be pulled into a folder called **themeforce** within your theme:

	../wp-content/themes/your-theme/framework/

## Activating within your Theme (functions.php)

We understand you may not want to use all the features, so it's only normal that you reduce the number of queries
that your theme executes. Our modular approach means that you can do just that. Just add any (or all) of the functions below to grab what you need (within **functions.php**).

// Set up theme supports

add_theme_support( 'tf_food_menu' );
add_theme_support( 'tf_events' );

add_theme_support( 'tf_widget_opening_times' );
add_theme_support( 'tf_widget_google_maps' );
add_theme_support( 'tf_widget_payments' );
add_theme_support( 'tf_foursquare' );
add_theme_support( 'tf_gowalla' );
add_theme_support( 'tf_yelp' );
add_theme_support( 'tf_qype' );
add_theme_support( 'tf_mailchimp' );

add_theme_support( 'tf_settings_api' );

	
The main file that brings everything together within the *"themeforce/** folder is is:

	framework/themeforce.php
	
## Using within your Theme	

If you'd like to learn how to use the Theme Force framework (i.e. shortcodes, widgets, etc.), please consult the **manual**:

* Manual: http://www.theme-force.com/members/manual/

## Contributing

We'd love to have your input, and if you're interested in contributing code, we'd love that too. Head over to http://www.theme-force.com/framework-developers/ for more information.
	
## Support

We can't actually help you with CSS, XHTML, PHP & JS so there's a certain degree of self-reliance that's required if you'd like to implement. It doesn't mean we won't guide you on the right path, but we'd like to keep the discussions relevant to bugs, enhancements and features.