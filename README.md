# static-wp
Plugin to serve up static twig templates from WordPress.

This plugin allows you to write simple HTML pages using Twig's templating language and set's up the route automatically. This is useful for developers that may want some pretty static HTML pages but don't want to set them up using WordPress's archaic theming.

## Installation

- Install and activate the plugin.
- Specify a directory for your twig files
- Filenames will be the corresponding route. `.` represents a `/` in the URL. So `about.me.twig` can be access at `https://yoursite.com/about/me`
- You also have some helper functions to access some WordPress functions. Oftentimes you may want to use the same stylesheets or even the same head that's used in your currently activated theme in order to share assets. This is drop and go with the same API.
