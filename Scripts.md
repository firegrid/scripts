Getting all files in a folder(Recursive)
---------------------------------------------
##### Windows

```batch
dir /s/b *.txt  
for /F "usebackq delims=" %a in ("files.txt") do (move %a "xxxlocation")
```
