##################
zip
##################

**zip** is an ``iterable object`` that provides an extremely useful technique to pack 2 different sequences
that are paired based on their positions and create tuples that bring in these
pairs together. For instance,

>>> Names = ['John','Jeanne', 'Roberto', 'Michelangelo']
>>> Citizenship = ['US','FR','MX', 'IT']
>>> for x,y in zip(Names, Citizenship):
...     print(x + ' belongs to ' + y)
...
John belongs to US
Jeanne belongs to FR
Roberto belongs to MX
Michelangelo belongs to IT

