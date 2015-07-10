correcthorse.wsgi
=========

An ansible role for configuring a wsgi app. At the moment this uses mod_wsgi but there may be other options in the future.

Role Variables
--------------

| Variables				| Default				| Notes					|
| :---					| :---					| :---					|
| wsgi_embedded				| false					| 					|
| wsgi_ignore_deprecation		| true					|					|
| wsgi_optimize				| 0					|					|

Dependencies
------------

  - correcthorse.common
  - correcthorse.python
  - correcthorse.httpd

Example Playbook
----------------


    - hosts: servers
      roles:
         - { role: correcthorse.wsgi }

License
-------

MIT

Author Information
------------------

* [Joshua Rusch](https://correct.horse/)
