## A autogen.sh Example
[![Build Status](https://travis-ci.org/shiffthq/autogen.sh-example.svg?branch=master)](https://travis-ci.org/shiffthq/autogen.sh-example)

A simple example for [autogen.sh](http://buildconf.brlcad.org/)

## .gitignore
Ignore all files generated by autogen.sh, except `configure.ac` & `Makefile.am`s.

## build result
As a library, the generated static/shared result located in `./.libs/`.
> ls -al ./.libs/

## make a dist version
> make dist

### list what in the archived file
> tar -tvf echo-0.1.0.tar.gz

## Refers
- [autogen.sh](https://sourceforge.net/projects/buildconf/)
