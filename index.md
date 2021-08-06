## Welcome to GitHub Pages
You can learn and colloborate on the page.
Thanks,
shunmuga.k

### VIM Cheat codes

Find the commands explored on the VIM codes

### Adding new lines bewteen each line:

```
%s/\(.\)\n\(.\)/\1\r\r\2/
```

### Delete lines except the string:

```
:%!awk -- '++c\%2
```


### Delete all lines in vim:

```
:1,$d
```

### Delete spaces b/w strings:

```
:'<,'>:s/\s\+/ /g
```

### intent:

```
select lines using CTRL + V and use " le 1 "
```
