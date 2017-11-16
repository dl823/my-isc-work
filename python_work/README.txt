PYTHON WOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOO (help me)


Dav 3... yea didn't bother with any of the stuff before. Go me...

>>> float(56.7)
56.700000000000003
>>> counter = 0
>>> while counter < 5:
...     print "Hello", counter
...     counter += 1
... 
Hello 0
Hello 1
Hello 2
Hello 3
Hello 4
>>> stuff = ['hello', 3, 3.555, 'bye']
>>> index = 0
>>> while index < 4:
... print index, stuff[index]
  File "<stdin>", line 2
    print index, stuff[index]
        ^
IndentationError: expected an indented block
>>> while index < 4:
...     print index, stuff[index]
...     index +=1
... 
0 hello
1 3
2 3.555
3 bye
>>> stuff
['hello', 3, 3.5550000000000002, 'bye']
>>> len(stuff)
4
>>> len ('hello')
5
>>> for item in stuff:
...     print item
... 
hello
3
3.555
bye
>>> x=1
>>> if x == 1:
...     print "HEYYYYYYYYYYYYYYYY"
... 
HEYYYYYYYYYYYYYYYY
>>> if x == 2:
...     print  2
... elif x == 1:
...     print 1
... 
1
>>> x = 0
>>> if x == 2:
...     print x
... elif x == 1:
... print x
  File "<stdin>", line 4
    print x
        ^
IndentationError: expected an indented block
>>> if x == 2:
...     print x
... elif x == 1:
...     print x
... else:
...     "HEYHEYHEY"
... 
'HEYHEYHEY'
>>> x=1
>>> x="boat"
>>> x[0]
'b'
>>> x[-2]
'a'
>>> x[1:3]
'oa'
>>> x[:3]
'boa'
>>> x[2:]
'at'
>>> x[:]
'boat'
>>> x
'boat'
>>> l=range(5)
>>> dir(l)
['__add__', '__class__', '__contains__', '__delattr__', '__delitem__', '__delslice__', '__doc__', '__eq__', '__format__', '__ge__', '__getattribute__', '__getitem__', '__getslice__', '__gt__', '__hash__', '__iadd__', '__imul__', '__init__', '__iter__', '__le__', '__len__', '__lt__', '__mul__', '__ne__', '__new__', '__reduce__', '__reduce_ex__', '__repr__', '__reversed__', '__rmul__', '__setattr__', '__setitem__', '__setslice__', '__sizeof__', '__str__', '__subclasshook__', 'append', 'count', 'extend', 'index', 'insert', 'pop', 'remove', 'reverse', 'sort']
>>> l.append('lunch')
>>> l
[0, 1, 2, 3, 4, 'lunch']
>>> l.remove'lunch'
  File "<stdin>", line 1
    l.remove'lunch'
                  ^
SyntaxError: invalid syntax
>>> l.remove('lunch')
>>> l
[0, 1, 2, 3, 4]
>>> t=(1,)
>>> print t[-1]
1
>>> l=range(100:200)
  File "<stdin>", line 1
    l=range(100:200)
               ^
SyntaxError: invalid syntax
>>> l=range(100-200)
>>> l
[]
>>> print l
[]
>>> l=range(100,200)
>>> l
[100, 101, 102, 103, 104, 105, 106, 107, 108, 109, 110, 111, 112, 113, 114, 115, 116, 117, 118, 119, 120, 121, 122, 123, 124, 125, 126, 127, 128, 129, 130, 131, 132, 133, 134, 135, 136, 137, 138, 139, 140, 141, 142, 143, 144, 145, 146, 147, 148, 149, 150, 151, 152, 153, 154, 155, 156, 157, 158, 159, 160, 161, 162, 163, 164, 165, 166, 167, 168, 169, 170, 171, 172, 173, 174, 175, 176, 177, 178, 179, 180, 181, 182, 183, 184, 185, 186, 187, 188, 189, 190, 191, 192, 193, 194, 195, 196, 197, 198, 199]
>>> l=range(100,201)
>>> tup = tuple(l)
>>> print tup[0], tup[-1]
100 200
>>> mylist = [23, "blah" 2.4e-10]
  File "<stdin>", line 1
    mylist = [23, "blah" 2.4e-10]
                               ^
SyntaxError: invalid syntax
>>> mylist = [23, "blah" 2.4]
  File "<stdin>", line 1
    mylist = [23, "blah" 2.4]
                           ^
SyntaxError: invalid syntax
>>> mylist = [23, "blah", 2.4]
>>> for (count, item) in enumerate (mylist):
...     print count, item
... 
0 23
1 blah
2 2.4
>>> (first, middle, last) = mylist
>>> print first, middle, last
23 blah 2.4
>>> (first, middle, last) = (middle, last, first)
>>> print first, middle, last
blah 2.4 23
>>> enumerate(mylist)
<enumerate object at 0x7fb9b76ef690>
>>> 
