
Tuesday January 11, 2022

Funny we are here one month later with more notes...

Ok, so first of all we are switching to a one command system...

prior we would have to go get the data  
then run a command...  
now we are going to just run the command.  
that will go out and grab the data  
and then do the processing and show a result.   

for now all of the data will be written to a configurable central location. the format of the data will initially be the exact same format we currently have but the data can be written to a configurable spot on the file system along with having a default location tambien.  for now the write and read will be to the file system and not a db.

Saturday December 11, 2021

These are my initial notes on the new design of this code...

First of all we will no longer have a dependency on redis, instead
we will use [tinydb](https://github.com/msiemens/tinydb).  This will
mean that developers of the future will not have to install redis on
their local boxes.

Second, the end user just has to provide a file with symbols in it.

The output will only be derived from yahoo finance data and no
other external data files or data sources.
