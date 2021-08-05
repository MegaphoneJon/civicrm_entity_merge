INTRODUCTION
------------

This module creates a cron job to look at any EntityReference fields you have that reference a CiviCRM contact, find any contacts that have been merged, and update the EntityReference field.


REQUIREMENTS
------------

This module requires the following modules:

 * CiviCRM
 * CiviCRM Entity

INSTALLATION
------------

Install as you would normally install a contributed Drupal module. See:
https://drupal.org/documentation/install/modules-themes/modules-7 for further information.

CONFIGURATION
-------------

There is no configuration - the cron job will run automatically.
