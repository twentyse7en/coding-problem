# Python tools
#### Character to integer
python has inbuilt function return an integer representing the Unicode code 
```py
>>ord("A")
>>65
```
### To combine elements in list to string
The join() method is a string method and returns a string in which the elements of sequence have been joined by str separator.
```py
>>list1 = [1, 2, 3, 4]
>>" ".join(str(x) for x in list1)
>>'1 2 3 4'
```
If the elements are in list are string, simply pass the list
```
>>list1 = ['1', '2', '3', '4']
>>" ".join(list1)
```
