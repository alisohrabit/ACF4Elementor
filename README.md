# Elementor ACF Widget Plugin

This is a sample plugin to demonstrate how you can write am extentions  to show a group of advanced custom fields in [Elementor]

Plugin Structure: 
```
assets/
      /js   
      /css  Holds plugin CSS Files
      
widgets/
      /acf4ele.php
      /inline-editing.php
      
index.php
elementor-ACF$ELE.php
plugin.php
```


* `assets` directory - holds plugin JavaScript and CSS assets
  * `/js` directory - Holds plugin Javascript Files
  * `/css` directory - Holds plugin CSS Files
* `widgets` directory - Holds Plugin widgets
  * `/acf4ele.php` - acf4ele demo Widget class
  * `/inline-editing.php` - Inline Editing demo Widget class
* `index.php`	- Prevent direct access to directories
* `elementor-acf4ele.php`	- Main plugin file, used as a loader if plugin minimum requirements are met.
* `plugin.php` - The actual Plugin file/Class.

For more documentation please see [Developers Website](https://avengering.com/en/how-to-create-an-elementor-widget-for-advanced-custom-fields/).
