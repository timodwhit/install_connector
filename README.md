INTRODUCTION
------------
Use case: You have a contrib profile and you need to install your custom
modules while still using the upstream profile without hacking. If this module
is in the upstream profile, it can be used to enable other modules from your
sites all directory.


REQUIREMENTS
------------
This module requires no additional modules to function.


INSTALLATION
------------
 * Install as you would normally install a contributed Drupal module. See:
   https://drupal.org/documentation/install/modules-themes/modules-7
   for further information.


CONFIGURATION
-------------
Add `$conf['install_connector_module'] = 'module_name'` to a settings.php.

FAQ
---
Q: How do I set the install connector module?

A: In a settings.php of your choosing, you can set the `$conf['install_connector_module'] = 'module_name'.

Q: Why not allow multiple modules?

A: This module only allows a single module because the dependencies for other
modules should be handled there.


MAINTAINERS
-----------
Current maintainers:
 * Tim Whitney (timodwhit) - https://www.drupal.org/user/1629156


This project has been sponsored by:
 * Miles
 Visit https://milespartnership.com
