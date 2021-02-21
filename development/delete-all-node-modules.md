Free up space on your HD by recursively deleting all node_modules within a given directory. 

Mac & Linux Downwards

```
find . -name "node_modules" -type d -prune | xargs du -chs
```
