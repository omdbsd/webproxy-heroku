## 本工程fork自 [h-n-p](https://github.com/gfw-breaker/heroku-node-proxy)
本工程是 [node-unblocker](https://github.com/nfriedly/node-unblocker) 的一个副本，只是修改了工程结构，以便于直接在Heroku上部署;  原作者的版本里, 所有的代理请求被到 http, 在该副本里，修改了代码让所有代理请求全使用https。

# 常见问题
1 不能打开heroku进行部署：heroku的登录/注册服务器已被 GfW 屏b，请翻墙进行部署（部署成功后不影响正常使用）

2 网站不能被打开，显示链接被重置：本品没有设置自动https访问，GFW升级过后，会检测访问链接来屏蔽某些敏感链接，某些设备可能会出现这种情况，遇到此问题时，请使用强制https访问的方法，就可以解决。同时，没有此问题的用户也强烈建议您使用强制https访问，安全性更高，不易被封。

# 注：此代理适用于大多数网站，但无法播放YouTube视频。

