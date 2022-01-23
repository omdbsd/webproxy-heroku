在该副本里，所有代理请求全使用https。

通过命令行部署
--------------

将代码clone到本地

```
$ git clone https://github.com/omdbsd/webproxy-hrk.git
```

创建heroku app

```
$ cd webproxy-hrk
$ heroku create my_h-n-p
```

将代码push到Heroku

```
$ git push heroku main
```

打开 https://my_h-n-p.herokuapp.com 即可使用。


-----

注：此代理适用于大多数网站，但无法播放YouTube视频。

