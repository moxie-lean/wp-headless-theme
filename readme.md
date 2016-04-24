# [Headless Theme](https://github.com/moxie-leean/wp-headless-theme)

> WordPress theme used on a architecture where the FrontEnd of a WordPress
site is handled using the Wordpress API.  

This theme prevents to render any other content from a regular
installation of WordPress.  

# Installation

This theme can be downloaded directly as a [zip](https://github.com/moxie-lean/wp-headless-theme/archive/master.zip) file or can be installed via composer.  

To install this theme via `composer.json` you only need to specify the
dependecy as follows: 

File: `composer.json`  

```json
{
  "name": "your-project-name",
  "require": {
    "moxie-lean/wp-headless-theme": "0.1.0"
  }
}
```

Or by running `composer require moxie-lean/wp-headless-theme` on your
terminal. 

And then run `composer install`.

Make sure to place this `composer.json` file at the root of your
WordPress installation since the theme is going to be placed
automatically at: `./wp-content/themes/wp-headless-theme`.
