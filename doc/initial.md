
Saturday December 11, 2021

These are my initial notes on the new design of this code...

First of all we will no longer have a dependency on redis.

Instead we will use an internal python dictionary that can get serialized,
or something to this extent.

Second, the end user just has to provide a file with symbols in it.

The output will only be derived from yahoo finance data.
