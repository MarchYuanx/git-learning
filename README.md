# Git Learning

## fixup 

init git log
```
feat: c
feat: b
feat: a
```

commit fixup c
```
git commit --fixup c
```
fixup git log
```
fixup feat: c
feat: c
feat: b
feat: a
```

squash
```
git rebase -i --autosquash b
```
rebase git log
```
feat: c
feat: b
feat: a
```