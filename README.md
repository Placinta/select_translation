drupal_select_translation
=========================

Drupal 7 port of Select Translation module.

This is based on the archive posted at https://drupal.org/node/1098708.
Given that the project seems abandoned, I hosted it on github.

It also includes a much better views filter handler that uses left joins instead of correlated (dependent) sub-queries,
which should prove to work much faster when there are a lot of nodes in the database.

Credits:
--------

citronica https://drupal.org/user/354488 and citronica's husband for providing the initial port

zuuperman https://drupal.org/user/361625 for the option_definition fix

The helpful people at stack overflow that helped optimize the query.
http://stackoverflow.com/questions/21985917/optimize-mysql-query-with-dependent-sub-query/21986190?noredirect=1#comment33324875_21986190

