_hello-simple_
==============

Example Haskell web application, to deploy with [Halcyon](http://halcyon.sh/) or [Haskell on Heroku](http://haskellonheroku.com/).

Written using the [Simple](http://simple.cx/) web application framework.


Usage
-----

### Deploying with Halcyon

With Halcyon installed:

```
$ halcyon deploy https://github.com/mietek/hello-simple
$ hello-simple
```


### Deploying with Haskell on Heroku

Ready to deploy to Heroku in two clicks.

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/mietek/hello-simple)

Alternatively, with Heroku Toolbelt installed:

```
$ git clone https://github.com/mietek/hello-simple
$ cd hello-simple
$ heroku create -b https://github.com/mietek/haskell-on-heroku -s cedar-14
$ git push heroku master
$ heroku ps:scale web=1
$ heroku open
```


About
-----

Made by [Miëtek Bak](http://mietek.io/). Published under the [MIT X11 license](http://mietek.io/license/).
