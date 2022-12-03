
# cut Command

Print selected parts of lines from each FILE to standard output.

**Command Switch**

____________________________

-   -d

    delimiter

-   -f (num)

    File Colum Word Number

```
cut -d" " -f1 file_name
```

```
cut -d":" -f1,2,3 file_name
```

```
cut -d":" -f1-10 file_name
```

```
cat file_name | cut -d" " -f1,2,4,7
```

```
grep "search choices" file_name | cut -d" " -f1
```

```
cut -d" " -f1-5 > new_file_name/old_file_name
```

```
cut -d" " -f >> old_file_name/new_file_name
```

