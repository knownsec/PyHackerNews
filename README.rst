PyHackerNews
============

.. image:: https://travis-ci.org/akun/PyHackerNews.svg?branch=master
   :target: https://travis-ci.org/akun/PyHackerNews
   :alt: Build Status

.. image:: https://landscape.io/github/akun/PyHackerNews/master/landscape.png
   :target: https://landscape.io/github/akun/PyHackerNews/master
   :alt: Code Health

.. image:: https://coveralls.io/repos/akun/PyHackerNews/badge.png?branch=master
   :target: https://coveralls.io/r/akun/PyHackerNews?branch=master
   :alt: Coverage Status

Hacker News written in Python

Install
-------

Features
--------

* [o] show news list

  + [o] show news list, order by score, with paginator
  + [o] show news list, order by post time
  + [o] show news info: title, domain, point, reporter, since when, comment count
  + [o] vote for news. **login required**
  + [o] remove news you post. **login required**

* [o] submit news

  + [o] submit news with title and URL/Content. **login required**

    - [o] URL for news
    - [o] leave URL blank to submit a question for discussion

* [o] comment

  + [o] show comment list order by score, with indent
  + [o] show comment info: comment words, point, who comment, since when
  + [o] copy comment link, in browser address input
  + [o] add comment abount news. **login required**
  + [o] reply the comment. **login required**
  + [o] vote for comment. **login required**
  + [o] remove the comment you add or reply. **login required**

* [o] Auth/Account

  + [o] login with social site's oauth

    - [o] GitHub
    - [o] Sina Webo

  + [o] show social site's oauth list
  + [o] edit personal account info: username, email(for gravatar). **login required**
  + [o] show someone account info: username for show, score, about

* [o] Hacker News Score System(auto)

  + [o] news score
  + [o] comment score
  + [o] user score
  + [o] calculate score in background

* [o] Customrize

  + [o] Title
  + [o] Copyright
  + [o] Google Analytics
  + [o] Bootstrap Themes

Contributing
------------

fork it and init env

::

   $ git clone git@github.com:yourname/PyHackerNews.git
   $ cd PyHackerNews
   $ virtualenv .
   $ source bin/activate
   $ make

add features or resolve bugfix, then run test

::

   $ make test

make pull request

License
-------

MIT
