## Unitex/GramLab Setup Installer for Unix-like systems [![Build Status](https://travis-ci.org/UnitexGramLab/unitex-packaging-unix.svg?branch=master)](https://travis-ci.org/UnitexGramLab/unitex-packaging-unix)

> [Unitex/GramLab][unitex] is an open source, cross-platform, multilingual, lexicon- and grammar-based corpus processing suite.

This script is used to create the [Unitex/GramLab][unitex] setup installers
for Unix-like systems.

### Script compilation
Usage:  
 `makenuis -DVER_MAJOR=# -DVER_MINOR=# -DVER_REVISION=# [OPTIONS] -DINPUT_BASEDIR=path`

For a full list of compiler flags supported by this program, just type
`makenuis` [return] at the command line. For a full list of
parameters and further information about the makeself.sh command, type
`makeself.sh` [return]. 

#### Example

1. Download the [Unitex/GramLab package](http://unitex.univ-mlv.fr/releases/latest-beta/source/Unitex-GramLab-3.1beta-source-distribution.zip)
   containing the Unitex/GramLab source distribution.
2. Unzip all files in a folder at one time.
3. Create the final setup installer typing:  
   `makenuis -DANONYMOUS_BUILD  -DINPUT_BASEDIR=path -DVER_MAJOR=number -DVER_MINOR=number -DVER_SUFFIX=suffix`  
   For example:  
   `makenuis -DANONYMOUS_BUILD  -DINPUT_BASEDIR=. -DVER_MAJOR=3 -DVER_MINOR=1 -DVER_SUFFIX=beta`  
   This will create an executable named: `Unitex-GramLab-3.1beta_anonymous_unix-setup.run`

### Setup installer command line parameters

The produced Unitex/GramLab setup installer accepts several optional
command line parameters. Some common options are:

| Option                     | Description                                           |
| -------------------------- | ----------------------------------------------------- |
| `/TODO`                    | TODO                                                  |

### Contributing

> Shell script code is ShellCheck-compliant. See http://www.shellcheck.net/about.html for information about how to run ShellCheck locally.

We welcome everyone to contribute to improve this project. Below are some of the
things that you can do to contribute:

-  [Fork us](https://github.com/UnitexGramLab/unitex-packaging-unix/fork) and [request a pull](https://github.com/UnitexGramLab/unitex-packaging-unix/pulls) to the [develop branch](https://github.com/UnitexGramLab/unitex-packaging-unix/tree/develop).
-  Submit [bug reports or feature requests](https://github.com/UnitexGramLab/unitex-packaging-unix/issues)

### Licensing information
This program is licensed under the [GNU Lesser General Public License version 2.1](/LICENSE). Contact unitex-devel@univ-mlv.fr for further inquiries.

--

Copyright (C) 2014-2015 Université Paris-Est Marne-la-Vallée

[makeself]:   http://stephanepeter.com/makeself
[unitex]:     http://unitexgramlab.org
