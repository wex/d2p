# D2

D2 Project is a lightweight PHP framework which can be used as Composer project 
to create your own software.

# How to get it?

  - You can use `git clone` to get it from GitHub
  - You can use Composer to install it as skeleton project: 
    `composer create-project nhujanen/d2p`

# How to use it?

  - After you have used Composer's create-project, you should do following:
    `cd d2p`
    `composer update`
  - Now you should configure your database credentials - those can be located
    from d2p/.config
  - Now you can continue set up process by:
    `composer setup`
    `chmod +x keen` (if you want to use Commander Keen)

# Requirements

D2P is requires PHP7.0 and is built over some other packages.

* [zendframework/zend-config] - Used in core configuration
* [zendframework/zend-db] - Used in ActiveRecord
* [zendframework/zend-diactoros] - Used in core request-response -routing
* [ramsey/uuid] - Used for UUID generation
* [filp/whoops] - Used for debugging
* [aura/router] - Used for routing
* [leafo/scssphp] - Used for realtime SCSS compiling
* [matthiasmullie/minify] - Used for realtime JS / CSS minifying

# What's up - why to use?

* Crypted sessions on database with custom session handling.
* Powerful ORM implementation with query builder & schema generator.
* Support for mixed CMS & MVC -mode.
* SCSS made easy - no more precompiling.
* Most straightforward View-Controller -implementation out there.
* Major CSS styling included (in SCSS ofc).
* Flexible routing.

# How to help?

At this point D2P is a one-man show. Architecture WILL be changed and some parts will be rewritten for sure.

# NOTICE!

Please do not use D2P in production before version `1.0.0` is released!

License
----

MIT