# foundation6

This is a theme for the static site generator [Nikola](https://getnikola.com) using the [Foundation](http://foundation.zurb.com) framework.

It aims to be simple, elegant and not bloat the overall size of your site too much.

## Usage

Go to the root directory of your Nikola site.

Create the `themes` folder in case it is missing:

  mkdir themes


Clone the repository as `foundation6` into the folder:

  git clone git@github.com:okin/nikola-theme-foundation6.git themes/foundation6


In your conf.py set `THEME` to `foundation6`.

Rebuild your site.

## Included in custom Foundation 6

This theme uses a custom Foundation 6 with fewer components to slim the size of the site even more.

Components used are:

* Grid, 12 Columns
* General
  * Typography
  * Visibility Classes
* Navigation
  * Menu
  * Accordion Menu
  * Top Bar
  * Pagination
* Containers
  * Callout
  * Table
* Media
  * Label

If you want to replace this with your own custom Foundation 6 - i.e. with different colors - just replace the foundation.min.css and foundation.min.js in the assets.

