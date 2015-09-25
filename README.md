
Drupal 7.x Book Export
======================

I'm tired of unable to nicely export and book created by the Drupal 7.x Book module and then import it fully into another Drupal site.  So I think I can write a module to do that.

Approach
--------

* The whole book is exported with Node export format.
* The export code can be imported with Node export, but book structure will be lost.
* Import with this module and the book structure will be recreated.
