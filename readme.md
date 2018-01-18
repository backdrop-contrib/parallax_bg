PARALLAX BACKGROUND
===================

This is a simple module that allows you to set a vertical parallax effect on the background of any element on the DOM.

You may have seen this technique in the "single page" websites that are often step based marketing pages for an event, company services or a new product.

<http://en.wikipedia.org/wiki/Parallax>

CONTENTS OF THIS FILE
---------------------

 - Tested
 - Known Issues
 - Special Thanks
 - Requirements
 - Installation
 - Coming From Drupal?
 - Permissions
 - Usage
 - License
 - Credits
 - Maintainers

TESTED
------

This module has been manually tested successfully creating several working JQuery parallax scrolling items in Backdrop.

KNOWN ISSUES
------------

This module works as is by just installing it.

This module bundles a third-party Javascript jQuery Parallax and jQuery.ScrollTo plugins from

<https://github.com/IanLunn/jQuery-Parallax/tree/master/scripts>

Version: 1.1.3 Author: Ian Lunn

Dual licensed under the MIT and GPL licenses: <http://www.opensource.org/licenses/mit-license.php> <http://www.gnu.org/licenses/gpl.html>

Probably the preferred way to do this module is to use the Libraries module to bundle instead like this documentation:
<https://www.drupal.org/project/scrollreveal>

If it bothers you that we don't use the Libraries module, file an issue and we can try to change it.

When official information on using third-party JQuery plugins becomes known, this will follow it.

SPECIAL THANKS
--------------

Big thanks to Ian Lunn for this functionality.

REQUIREMENTS
------------

A "parallax scrolling" looking website often has to use these four modules together:

- parallax_bg
- scrollreveal
- void_menu
- back_to_top

INSTALLATION
------------

Install this module using the official Backdrop CMS instructions at https://backdropcms.org/guide/modules


COMING FROM DRUPAL?
-------------------

Nothing substantially different.

PERMISSIONS
-----------

@todo


USAGE
-----

Go to admin page in /admin/config/user-interface/parallax_bg

Define the element you want to apply the parallax effect using any valid jQuery selector. The selector should point to the element that holds the background, for example: #top-content, body.one-page #super-banner

The background may be defined in the css of your theme, per example:

    body {
      height: 100%;
      background-image: url("background.jpg");
      background-attachment: fixed;
    }

Additionally you need to define the inertia (relative speed) of the background and its horizontal position.

Depending on the position of your element, you need to apply some top-padding to align the background when entering viewport.

LICENSE
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.

CREDITS
-----------

This module is based on the Parallax Background module for Drupal, originally written and maintained by a large number of contributors, including:

- hatuhay <https://www.drupal.org/u/hatuhay>

MAINTAINERS
-----------

- seeking

Ported to Backdrop by:

 - biolithic <https://github.com/biolithic>
