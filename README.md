# Full-Unicode-list-supported-by-python
This is a full Unicode list supported by python by using a simple unicode printer using utf-8.
i have removed spaces and enters for user conviniance and i will put a single list and
a compacted one aswell for different perposes, there are around 1000 characters (exactaly)

# code
```
with open('your file with .txt', 'w', encoding='utf-8') as file:
   for i in range(0, 1114112):  # Unicode range
      print(chr(i), end=' ', file=file)
```
## breakdown
```
with open('your file with .txt', 'w', encoding='utf-8') as file:
```
This ^ opens the file in write mode and encodes it using utf-8 that is unicode
```
for i in range(0, 1114112):  
```
This ^ creates the unicode range used to print
```

```
