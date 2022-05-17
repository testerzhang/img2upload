# img2upload
----
🔥配合typora的自定义图床后端程序



##  说明

* 本仓库提供一个小工具,适用Linux系统。

* 配置文件修改

```
# 启动服务的端口
port: 5432
# 存放的本地路径
store_path: "./uploaded"
# nginx不带路径
nginx_url_path: http://127.0.0.1:5432
# 显示图片:  nginx_url_path后面带的url前缀
url_prefix: "/uploaded/"
```

* 启动方法

```
$ nohup ./img2upload &
```



## 文章说明

[Markdown图床：typora自定义上传图片到服务器，完美](https://mp.weixin.qq.com/s/ILgLCp1F3HCAOF0_ZiicCA)



## 欢迎订阅

![gzh](https://testerzhang.github.io/resources/gzh.png)

