
Saturday December 11, 2021

These are my initial notes on the new design of this code...

First of all we will no longer have a dependency on redis, instead
we will use [tinydb](https://github.com/msiemens/tinydb).  This will
mean that developers of the future will not have to install redis on
their local boxes.

Second, the end user just has to provide a file with symbols in it.

The output will only be derived from yahoo finance data and no
other external data files or data sources.
