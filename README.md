# Autotools-package for [makeheaders](http://www.hwaci.com/sw/mkhdr/)

This simply eases of installation `makeheaders`, the awesome utility from the same prolific guy that wrote [Sqlite](https://sqlite.org/), [fossil](http://fossil-scm.org/) and [lots of other badass stuff](http://www.hwaci.com/sw/).  

The `makeheaders` reads through C/C++ source code and generates an appropriate corresponding header (.h or .hpp).  It can also generate external library headers.



### Try out `makeheaders` (without installing)

	git clone https://github.com/steakknife/makeheaders
	cd makeheaders
	./bootstrap && ./configure && make
    

### Install `makeheaders` to `/usr/local/bin`

    # add sudo before `make` if you need permission
    ./bootstrap && ./configure && make install


### Install `makeheaders` to `/opt/whatever/bin`

    # add sudo before `make` if you need permission
    ./bootstrap && ./configure --prefix=/opt/whatever && make install


## Documentation

[Original upstream doc here (html)](http://www.hwaci.com/sw/mkhdr/makeheaders.html)

## Versioning

#### Format: Semantic versioning with hyphenated releases.

The verson part **before** the `-` indicates a change in source code.

A bump in version **after** the `-` indicates build or documentation related changes.


### About autotools packages

Autotools packages are super old school and work on just about every
*NIX system with autotools (one common example: [GNU](https://www.gnu.org)'s [m4](https://www.gnu.org/software/m4/), [autoconf](https://www.gnu.org/software/autoconf/) and [automake](https://www.gnu.org/software/automake/)).

`./bootstrap` calls autotools scripts that generate portable scripts that comprise configure.  The more familiar `./configure` generates a `Makefile` for your system so `make` knows what to do.

In case you've never worked with them before, this package right here
is the absolute simplest autotools package you could possibly find.   
This whole package is built around ONE source code file.

## License

[BSD (2-Clause)](http://opensource.org/licenses/BSD-2-Clause)

## Credit

### Updated fork credit
Barry Allard
2014

### Original fork credit
Shawn Wilson
Dec 2011

### Original upstream

Copyright 1993 D. Richard Hipp. All rights reserved.

v1.4 2005/03/16 22:17:51

[http://www.hwaci.com/sw/mkhdr/index.html](http://www.hwaci.com/sw/mkhdr/index.html)

