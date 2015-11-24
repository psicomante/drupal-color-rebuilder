Color Rebuilder
===============

This module allows to clear the images and css cache of the color module.
It allows to set a new color scheme for a specified theme.

It supports Drush and Hook_Menu

##Rebuild using URL

Load the page

```
http://drupalsite.com/color_rebuilder/rebuild/<theme_name>/<color_scheme>
```

## Rebuild using Drush


```
cd <module-site-folder>
drush en color
drush en color_rebuilder
drush creb --theme=<theme-name> --scheme=<scheme-key>"
```

Example:

```
cd /var/www/drupal
drush en color
drush en color_rebuilder
drush creb --theme=garland --scheme=chocolate"
```

Reload the page and you can see the new theme color.

Acknowledgments
===============

[Skylogic](http://www.skylogic.it)
[Polymole - Drupal and Computer Graphics](http://polymole.it)

