Webform Autocomplete
======================

This module extends the Webform module by adding a new component type:
Autocomplete.

An autocomplete is a textfield that automatically suggests values as the user
types. You may pre-populate your autocomplete with values, and/or it can suggest
values from previous submissions.

Important note: If you choose to autocomplete from previous submissions, this
gives others the ability to see all previous entries for that field. Do not use
this feature with private, personally identifying information.

This module is based on the 7.x-2.x branch of the Drupal version of Webform
Autocomplete, and so works with the Backdrop version of Webform, which is based
on the 4.x version of Drupal Webform.

The Drupal version of this module is compatible with [Form
Builder](https://www.drupal.org/project/form_builder). There is not yet a
Backdrop port of Form Builder, but we are leaving in the Form Builder hook
implementations against that eventuality.

Installation
------------

- Install this module using [the official Backdrop CMS instructions](  https://backdropcms.org/guide/modules).

- There is no global configuration page for the module.

Usage
------------

- When you create a new Webform, there will be a new Autocomplete component choice.


Documentation
-------------

Additional documentation is located in [the Wiki](https://github.com/backdrop-contrib/webform_autocomplete/wiki/Documentation).

Issues
------

Bugs and feature requests should be reported in [the Issue Queue](https://github.com/backdrop-contrib/webform_autocomplete/issues).

Current Maintainers
-------------------

- [Robert J. Lang](https://github.com/bugfolder).

Credits
-------

- Ported to Backdrop CMS by [Robert J. Lang](https://github.com/bugfolder).
- Originally written for Drupal by [Coleman Watts](https://www.drupal.org/u/colemanw).
- Initial development sponsored by [WeDivest.org National Coordinating Committee](http://wedivest.org/)

License
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.

