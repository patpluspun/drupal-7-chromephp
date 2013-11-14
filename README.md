drupal-7-chromephp
==================

A Drupal module that enables the ChromePhp chromelogger extension for permissioned users.

First you must acquire this library through some means: [ChromePhp](https://github.com/ccampbell/chromephp).

Then create a folder named "ChromePhp" in your sites/all/libraries directory.  If sites/all/libraries does not exist,
create it.

Ensure that ChromePhp.php is directly inside the ChromePhp folder and enabled the module!

It comes with one function for now, `cpm()` that works much like `dpm()` except it prints to the console instead of Drupal's
messages area.
