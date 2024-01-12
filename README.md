# Issue Tracking System 

Overview
--------
This Drupal module provides functionality for tracking and managing 
issues within the Drupal site.It includes a block that displays 
the latest assigned issues for the current user.

Warning:
--------
This module is developed and designed for Drupal 8-9-10 only.

Features:
--------
- Latest Assigned Issues Block: Displays the three 
  latest issues assigned to the current user.
- Issue Content Type: Utilizes a custom content type 'issue' to 
  store information about individual issues.

Installation adn Enabling
------------
1. Enable the module using Drush or through the Drupal administrative interface.

   ```drush
   drush en issue_tracking_system
   
2. Download and place the module in your Drupal custom module directory.
   (e.g. modules/custom/issue_tracking).

3. To install module with Drupal console, execute the command below:

  ```Drupal Console
   drupal moi module_name
