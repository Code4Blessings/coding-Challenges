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

`count` gives you how many instances of x occur inside the array




