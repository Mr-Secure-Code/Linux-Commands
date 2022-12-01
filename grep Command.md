
# grep Command

Prints lines that contain a match for one or more patterns..

```
grep -i search_choices file_name
```

```
grep -n search_choices file_name
```

```
cat file_name | grep search_choices
```

```
ps -aux | grep -i search_choices
```

```
grep -E '(search choices 1| search choices 2)' file_name
```

```
grep "^search choices" file_name
```

``` 
grep "search choices $" file_name
```

``` 
grep "search choices" file_name
```

```
cat -n file_name | grep search_choices
```

```
grep -n search_choices file_name >> "new file name"
```

```
grep search_choices file_name >> "old file name"
```

```
grep -inE "(search choices 1|search choices 2)" > "old file name"
```
