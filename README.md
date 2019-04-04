# 基于nodejs的excel表格合并工具

### 背景

最近在搞基于NodeJs的爬虫抓取数据<br>
为了让抓取数据更加稳定且不导致nodejs线程阻塞，所以进行了分段抓取<br>
例如抓取1万条数据，分成了20个excel文件<br>
但是几十个excel文件分别导入到数据库中，操作繁琐且麻烦，那么将多个excel文件合并后导入数据库是一个不错的方法（大家如果有其他好的方法可以在评论里聊一聊哈）<br>
本想用wps去合成，结果发现它居然要登录且开会员！！又懒得去装新版的office（手动滑稽）

### 正确的食用姿势

1. 把需要合并的文件放到excel文件夹里
2. 运行start.bat文件
3. 到result下拿到合并完成的excel

### 运行

```bash
$ npm i
$ npm run start
```

#### 注意

excel文件里的字段要保持一致哦

[github]: https://github.com/cmyh100
[CSDN]: https://blog.csdn.net/cmyh100