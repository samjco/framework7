# framework7
examples and tests with framework7 (from idangero.us) and WordPress

## 1 - Template7 Pages for WordPress

This example is the result of tests to learn famous Framework7 with WordPress.
This is based on examples available in http://www.idangero.us/framework7/examples/
This example is published to open discussion and improvements...

### Prerequisites

A (local or not) WordPress website as json server (needs json plugin https://wordpress.org/plugins/json-api/ ).
This plugin is able to deliver json file that will be incorporated in latest posts page of webapp.

URI must be adapted to your config in function  $$.getJSON of my-app.js - now via Settings popup form

The webApp uses Framework7 v. 1.0.4 (updated March 22th, 2015)

Tested also with an iPad Air retina (via browser or as webapp installed in iPad homepage)

### installation

- install the folder in a (local) server
- modify the URI of the WP website to keep json (verify that the apache server is ready to deliver json for IP client - .htaccess)

### Done

- form to choose URI of WP server
- caching of Json Datas
- insertion of thumbnail_images if available
- better var

### Pending issues

- X refreshing excepted:'? with post.html ever in cache if home iOS webApp'
- X caching (partially)
- abstraction layer between json and f7 datas (to merge the both examples)
- full off line
- doc

### Projects

- more integration with WordPress themes
- ...

- french speaking references tips and tricks website

michelwppi dev.xiligroup 2015-03-27