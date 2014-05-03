wp-phinx
========

Proper database migrations for WordPress using [Phinx](https://github.com/robmorgan/phinx)

* Install the plugin (doesn't even need to be activated)
* Run sudo ln -s {{PLUGIN_DIR}}/wp-phinx/vendor/bin/phinx /usr/local/bin/
* Change to directory where you will manage migrations (probably a plugin...)
* mkdir migrations && phinx init
* Follow instructions at link above
