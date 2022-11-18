```shell
##如果已经有过提交，修改了 .gitignore 文件，导致 过滤不生效，就需要使用以下命令解决：

     git rm -r --cached .
 
     git add .
 
     git commit -m 'update .gitignore'
```

