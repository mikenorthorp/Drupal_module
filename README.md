README
======

README and code base best viewed on [Github](https://github.com/mikenorthorp/Drupal_module)

This is an assignment for my Server Side Scripting class INFX2670 Assignment 3

This is a custom module written for drupal. It contains a basic form with various elements that you can submit. This form saves to a database which then gets pulled on a view page in the module to see all the submission entries. There is also a configuration page to enable / disable fields on the form and display page. This module uses custom permissions, validation checks, and many of the different APIs drupal has to offer. 

The entire drupal codebase is in the source, but the main module is located in /sites/all/modules/infx2670northorp

Requirements
------------

This program requires `drupal 7.x`, `php` and `apache` to be installed on the server you are running this on.

Installation
------------

1. Navigate to /sites/all/modules/infx2670northorp
2. Copy the infx2670northorp folder into the same directory on your own drupal installation. 
3. Enable the module under modules in drupal.
4. Give the custom permission added to a user of your choice if you want to delete form submissions. (usually admin)
5. Play around with the added pages in the module and the configuration page.

The urls to go too are:

`Form Page = /infx2670northorp/form`
`View Form Page = /infx2670northorp/form`
`Admin Config Pag = /admin/config/content/infx2670northorp`

Making the Website Do Things
----------------------------

1. Add submissions to the form page.
2. View submission on the view page.
3. Delete submission on the view page if you have permissions.
4. Play around with config settings to enable / disable fields.


Citations
=========
Lecture notes and code used and modified, various stack overflow posts read, drupal docs heavily read and modified code examples from drupal docs.




