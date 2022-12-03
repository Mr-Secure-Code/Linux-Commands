
# awk Command

Filter line And Colum in File.

```
awk '{print $1}' file_name
```

```
awk '{print $1,"-",$10}' file_name
```

```
awk '{print $1,$5}' file_name
```

```
cat file_name | awk '/search_name/{print $1}'
```

```
awk '{print $0}' file_name
```

```
awk '/$1==search_name{print $0}'
```

```
awk '$1!=search_name{print S0}'
```

```
awk 'BEGIN {print "Your_Choice_Print"} {print $1} END {print "Your_Choice_Print"}'
```

```
awk 'BEGIN {print "Your_Choice_Print"} /search_name{print $0} END {print "Your_Choice_Print"}'
```
