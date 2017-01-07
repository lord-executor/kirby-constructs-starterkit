# Overview
This project is a demonstration of some of the capabilities of the [Kirby Constructs Plugin](https://github.com/lord-executor/kirby-constructs).
It is based on the [Kirby Starterkit](https://github.com/getkirby/starterkit) with some minor functional tweaks and
content that demonstrates some of the Constructs Plugin capabilities.

# Getting Started
Clone this repository
```
git clone --recursive https://github.com/lord-executor/kirby-constructs-starterkit.git
```

If you have PHP 7 or greater (there is an issue with the routing script for older PHP versions), you can run this Kirby
instance with the built-in PHP server by changing into the `web` directory and running the server with the
`kirby-router.php` routing script.
```
cd kirby-constructs-starterkit/web
php -S localhost:8080 kirby-router.php
```

Then open the URL [http://localhost:8080/](http://localhost:8080/)

If you **don't** have PHP 7 or greater, then you can just point your webserver to the `web` directory like any other
Kirby install and everything should work as usual.

# Now What?
Check out the `web/site/constructs/sample-construct` for the sample code and configuration together with the
`web/site/content` to see how the page is constructed - of course you can also use the Panel UI to investigate the
content structure.

And of course you should have a look at the [Kirby Constructs Plugin Documentation](https://github.com/lord-executor/kirby-constructs).
