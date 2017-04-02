# Java Thread Dump Analyzer [![Build Status](https://travis-ci.org/mpobjects/threaddump-analyzer.svg)](https://travis-ci.org/mpobjects/threaddump-analyzer)

This is a Java thread dump analyzer written in Javascript. Based on the 
[original version by Spotify AB](https://github.com/spotify/threaddump-analyzer).

**[Click here to get your Java thread dump analyzed.](https://jstack.review)**

# License

The Java Thread Dump Analyzer is licensed under [version 2.0 of the Apache license](http://www.apache.org/licenses/LICENSE-2.0.html).

* Copyright 2014-2016 Spotify AB
* Copyright 2016-2017 MP Objects BV

## TODO

* [Stuff from the upstream TODO list?](https://github.com/spotify/threaddump-analyzer/blob/gh-pages/README.md)
* ~~Compare two threads~~
* Improve/extend unit tests
* Expose configuration settings on the screen
   * Saving of settings for future use
* Support all thread dumps from the [TDA tests](https://github.com/irockel/tda/tree/master/tda/test/none) 
* Allow importing of a dump posted on gist/pastebin/... via url
   * Importing works for github/gist hosted content, e.g. https://mpobjects.github.io/threaddump-analyzer/?https://github.com/irockel/tda/blob/master/tda/test/none/java8dump.log
   * pastebin/pastee do not work due to CORS, are there other snippet hosting sites which do have an open CORS?
   * need to improve error reporting
* define (configurable) package patterns to collapse stack traces after N lines when the stack trace is M lines long
* ...
