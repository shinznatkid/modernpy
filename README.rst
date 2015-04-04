********
Modernpy
********

Extension methods for built-in type in Python.

Usage
########

Integer
--------
(123).instance_of(int)
(123).to_s()
(123).to_f()

Float
--------
(123.45).instance_of(float)
(123.45).to_s()
(123.45).to_i()

String
--------
"hello".instance_of(str)
"hello".length
"123".to_i()
"123.45".to_f()
"hello".to_s()

Unicode
--------
u"hello".instance_of(unicode)
u"hello".length
u"123".to_i()
u"123.45".to_f()
u"hello".to_s()

List
--------
[1, 2, 3, 4].instance_of(list)
[1, 2, 3, 4].length
[1, 2, 3, 4].sum()

Tuple
--------
(1, 2, 3, 4).instance_of(tuple)
(1, 2, 3, 4).length
(1, 2, 3, 4).sum()
