## Given-a-Python-list-remove-all-occurrence-of-20-from-the-list
## Sample code to check the details in python list and remove all the occurence
```sh
def removeValue(sampleList, val):
   return [value for value in sampleList if value != val]
resList = removeValue(list1, 20)
print(resList)
```
## Example output
[5, 15, 25, 50]
