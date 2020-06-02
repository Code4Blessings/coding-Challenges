# List Methods

1. `index` - returns the index of a specified item in a list

```
>>> numbers = [5, 6, 7, 8, 9, 10]
>>> numbers
[5, 6, 7, 8, 9, 10]
>>> numbers.index(7)
2
>>> 

```

 `index` can also specify start and end.

 ```
 >>> numbers2 = [5,5,5, 6,7, 7, 8, 9, 10]
>>> numbers2
[5, 5, 5, 6, 7, 7, 8, 9, 10]
>>> numbers2.index(5, 1) **This says find the first instance of 5 starting at index 1**
1
>>> numbers2.index(7, 3, 6) **This says find the first instance of 7 between index 3 and 6**
4
```

2. `count` gives you how many instances of x occur inside the array

```
numbers2 = [5,5,5, 6,7, 7, 8, 9, 10]
>>> numbers2.count(5)
3
>>> numbers2.count(7)
2
>>> numbers2.count(12)
0
```

3. `reverse` reverses the elements in the list

```
>>> numbers = [5, 6, 7, 8, 9, 10]
>>> numbers
[5, 6, 7, 8, 9, 10]
>>> numbers.reverse()
>>> numbers
[10, 9, 8, 7, 6, 5]

```

4. `sort` sorts the elements in a list










