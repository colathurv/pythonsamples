##################
map
##################

**map** is an ``iterable object`` that provides an extremely useful technique to apply
a function on all elements of a list. For instance, I have found this very handy where
in I want a bunch of consecutive Integers that represent a Year to be column indexes of a dataframe.
What is happening here is that a range of consecutive integers starting from 2006
and ending at 2015, have all been converted into a list of strings, using map.

>>> list(map(str, range(2006, 2016)))
['2006', '2007', '2008', '2009', '2010', '2011', '2012', '2013', '2014', '2015']

