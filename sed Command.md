
# sed Command

Stream Editor for filtering and transforming text.

-   p

    print
-   a

    appand

-   g

    globle

-   i

    insert

-   e

    Exuited Command

-   c

    change

-   -i

    save file

-   -n

    silent

```
sed  -n '1p' file_name
```

```
sed -n '/search_name/p' file_name
```

```
sed '2!p' file_name
```

```
cat file_name | sed 's/root/ROOT' 
```

```
sed 's/root/ROOT/g' file_name
```

```
ps -aux | sed 's/root/ROOT/g' > new_file_name
```

```
sed '1-4 s/search_name/change_search_name' >> old_File_name
```

```
sed '1-$/p'  file_name > old_File_name
```

```
sed '^-4/p' file_name >> new_file_name
```
