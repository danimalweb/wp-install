# wp-install

Bash script for easily installing WP with additional dependencies.


# Dependencies #

### wp-cli ###

You can install the latest version of wp-cli to `/usr/bin` by running `./get-wp-cli`.


# Installation #

Copy `wp-install` to somewhere on your `path`. `/usr/bin` might be a good choice.

	sudo cp wp-install /usr/bin/wp-install


# Usage #

 1. `wp-install`
 2. Follow instructions
 3. Appreciate free time


# Features #

* Config file for pre-population of email address, username, default theme to install
* Comes with options to install common plugins
  * Yoast SEO
  * Regenerate Thumbnails
  * Contact Form 7
  * Wordpress Sync DB
* Supports NPM, Bower and Composer
* Automatically blocks search engine spiders
* Deletes sample posts and pages
* Create and assigns home page
* Creates additional pages
* Sets up pretty urls
* Deletes hello dolly plugin
* Add custom post types and taxonomies during install.
