# pythonSpider
some python spiders with BeautifulSoup

## githubSpider

###githubFollowXXList 模块：

```
get_follow_counts_pages(url,person,boo)：
```

**url**就是github的网址：'https://github.com/'；

**person**是想要获取用户的username；

**boo**是一个布尔值,若是真，则获取following，若是假，则获取followers

可以获取当前人物的获取following或者followers的页数

```
get_follow_lists(url,person,boo，pages)：
```

**url**, **person** ,**boo**和上一个方法一样，**pages**是指想获取第几页的following或者followers的列表

方法返回当前page的following或者followers的列表，结合
```
get_follow_counts_pages
```
可以获取所以的following或者followers的列表