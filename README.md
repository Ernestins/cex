# cex
condoc enviroment for executions (cex) is a static site generator

With 
```bash
$ cex init myprojectname
...
```

$ cex get https://dex.github.com/dexstyles/book-a4-base.git
target book
...
Writing book.yml

$ cex add https://gitserver.com/webskel/Website-mds.git
target website main pub https://Web.com/.git

...
Writing main.yml
Writing web/deploy-main--gut

$ cex add https://gitserver.com/webskel/website-simple.git
target website backup pub ftp://user:pass@web.com/~user
...
Writing backup.yml
Writing web/deploy-backup-user-ftp

$ cex add target s5 blue-theme
...

$ cex add target s5-handout-3x white-theme
...


$ cex make all
...

$ cex publish all
...
```
