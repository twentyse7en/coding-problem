# Python tools
#### Character to integer
python has inbuilt function return an integer representing the Unicode code 
```py
>>ord("A")
>>65
```
#### To combine elements in list to string
The join() method is a string method and returns a string in which the elements of sequence have been joined by str separator.
```py
>>list1 = [1, 2, 3, 4]
>>" ".join(str(x) for x in list1)
>>'1 2 3 4'
```
If the elements are in list are string, simply pass the list
```py
>>list1 = ['1', '2', '3', '4']
>>" ".join(list1)
```
#### Map
map() function returns a map object(which is an iterator) of the results after applying the given function to each item of a given iterable (list, tuple, string etc.)
```py
>>>map(func, iter)
```
#### Zip
The purpose of zip() is to map the similar index of multiple containers so that they can be used just using as single entity
```py
>>name = [ "alpha", "beta", "gamma"] 
>>value = [ 1, 2, 3]
>>zip( name, value)
>><zip at 0x7fe9500a7780>
```
