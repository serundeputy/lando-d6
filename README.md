Drupal 6 Example
----

Lando is a dependency:
  * [lando](https://github.com/kalabox/lando)
  * [lando docs](https://docs.lndo.io/)

----
This is a Drupal 6 example using php 5.3 so you can run old drupal apps and its
modules that may not cooperate with newer versions of php.

The important parts here are the `config` directory and the `.lando.yml` file.

----
If you want to put your own D6 app in place just remove the `www` directory and
put your D6 app into a new `www` directory. Then the command `lando start` will fire up your Drupal 6 app.

To bring the app down use: `lando stop`.

----
Use the command:
  * `lando info`

to get info about the app.  For example you can use the database info to connect to the container DB with the command line or Sequel Pro.
