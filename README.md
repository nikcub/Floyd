# Floyd v0.0.3a12

Latest update: Thu Apr 19 01:01:38 EST 2012

An advanced MVC CMS that generates static sites for Google AppEngine and Amazon S3

Usage: `floyd <sources> <outputdir>`

# Features

 * Full MVC - define your routes, controllers, etc. and then generate
 * Full data model (eg. `floyd.db.Query('Posts').filter(post_type='page').order('-datetime').fetch()`)
 * Data model reads from flat source files
 * Convert text, markdown or HTML pages into HTML output
 * Automatically configures AppEngine sites
 * Supports different templating engine (defaults jinja2)

# Install

    $ pip install floyd

or if you don't have pip you can use easy_install (default on OS X and with python installations on other platforms)

    $ easy_install floyd

For more information see INSTALL
