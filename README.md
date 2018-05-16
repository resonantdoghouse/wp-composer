## Composer & WordPress

Development setup using Composer to add WordPress as a dependency.

In the app folder there are themes and plugins for testing, some maybe some interesting solutions to common WP puzzles.

### Intsall

If you don't have Composer installed... Start here: [Composer Install](https://getcomposer.org/doc/00-intro.md)

To install wordress, plugins & themes run:

`composer install`

& if adding packages after installing run: 

`composer update`

You will need to **update wp-config.php**
& add a database.

**wp-content** has been 'moved' plugins & themes are now in the 'app' folder.

