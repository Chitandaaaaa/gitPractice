#### 第一次提交代码，但是 `.ignore` 未提交。
```
git rm . -rf --cached
git add .
git commit -m 'add .ignore'
git push origin master -f
```