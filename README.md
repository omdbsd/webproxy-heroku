本工程fork自 [h-n-p](https://github.com/gfw-breaker/heroku-node-proxy)
-----


本工程是 [node-unblocker](https://github.com/nfriedly/node-unblocker) 的一个副本，只是修改了工程结构，以便于直接在Heroku上部署;  原作者的版本里, 所有的代理请求被到 http, 在该副本里，修改了代码让所有代理请求全使用https。

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


## 注：此代理适用于大多数网站，但无法播放YouTube视频。

