# 100DaysOfDataStructureAndAlgorithm

## Day1: Binary Search using python's Bisect Method:
[Bisect](https://docs.python.org/3/library/bisect.html) in python takes sorted array as input and return index corresponds to related values. **The method search for index of left/right element that the searched element could have.** This method uses binary search algorithm internally. 
* `bisect_left` - for finding left element index correspond to search element, if exact element found it will return the index of exact element
* `bisect_right`/ `bisect` - for finding right element index correspond to search element, if exact element found it will return index of right next element
### Input:
```
import bisect
arr = [1, 2, 3]
print(bisect.bisect_left(arr, 1)) # find index of element
print(bisect.bisect_left(arr, 6)) # if element is not present it will find the index of the left element, the search element should have
print(bisect.bisect_right(arr, 1)) # it find index of right element that the search element could have
```
### Output:
```
0
3
1
```
Related [Video](https://www.youtube.com/watch?v=mqaf7vj1AdA&list=PL5tcWHG-UPH1K7oTJgIbWy6rCMc8-8Lfm&index=19)
