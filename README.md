Standard Edtion
===============

Features
--------

* symfony3 structur (as far as known)
* doctrine2 migrations
* npm assets management
* bootstrap3 framework

Installation
------------

```bash
composer install
npm install
```

Run application
---------------

```bash
bin/console server:run
```

Assets
------

Your assets should be in `assets` folder and gulp should copy (minified and concated) it to the web directory.
By installation your assets automaticaly will copied in the web directory.
If you in development, you can watch your assets with following command:

```bash
# shortcut to run gulp watch ;-)
npm start
```

Tests
-----

You should add your tests in the `tests` folder.

```bash
bin/phpunit
```

Todo
----

* puli integration
