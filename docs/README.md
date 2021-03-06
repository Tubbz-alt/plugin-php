# Athena PHP Plugin

Athena PHP Plugin is a plugin for [Athena](https://github.com/athena-oss/athena), that provides a PHP environment for you to execute and create different types of tests, and provides a fluent interface to short-cut and ease test development for PHP.

For Tests that require `Selenium` and/or `Proxy` you also need to install the [Athena Selenium Plugin](https://github.com/athena-oss/plugin-selenium) and/or [Athena Proxy Plugin](https://github.com/athena-oss/plugin-proxy).

## Main Features

* Supported Testing types :
	* API (using BDD or classic approach)
	* Browser (using BDD or classic approach)
	* Unit
	* Lint
	* Checkstyle
	* Complexity
* Parallelism
* Reports with Screenshots for when using Selenium driver (HTML)
* Reports with HTTP transanctions exposed (HTML)
* And many many more...

## How to Install ?

To install it simply run the following command :

```bash
$ athena plugins install php https://github.com/athena-oss/plugin-php.git
```

or

* On MAC OSX using [Homebrew](http://brew.sh/) :
```bash
$ brew tap athena-oss/tap
$ brew install plugin-php
```

Read the [Documentation](http://athena-oss.github.io/plugin-php) on using Athena Plugin PHP.


## Using the Plugin

```
$ athena php

...

usage: athena php <command> [<args...>]

These are the available commands for plugin [php]:
	api        Run api tests.
	bdd        Run behaviour driven tests.
	browser    Run browser tests.
	cleanup    Removes vendor related stuff.
	lint       Check files for syntax errors.
	phpcs      Analyse code smells against a custom or existing rule-set.
	phpmd      Run mess detector tests
	self-test  Executes tests to the built-in functionalities.
	unit       Run unit tests.

```
