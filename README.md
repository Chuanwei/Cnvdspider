# 这是什么 #
>这是一个每天对cnvd重大安全漏洞，每天定时在固定时间端爬取漏洞通告，并以邮件的方式发送到自己的邮箱达到一个邮件预警的作用

# 如何安装 #
``` bash
root$:git clone https://github.com/LiodAir/Cnvdspider.git

root$:cd Cnvdspider

root$:pip install requirments.txt

root$:cp -a geckodriver /usr/local/bin/

我的运行环境：centos6.9、firefox52、geckodriver0.17.0x64、python2.7
```
>以及一个如何安装自动化selenium webdriver 的资源连接[how to install selenium](https://www.jianshu.com/p/08d8aa49c553?utm_source=oschina-app)，我相信一个`爱折腾`的这点问题不是难度的



## 然后修改配置文件 ##

```root$:sudo vim main.py```

![修改发送邮件的邮件服务器](https://github.com/LiodAir/Cnvdspider/blob/master/images/code.png)
>然后修改setting.py文件，修改每天脚本发送邮件的对象

# 运行状态 #
``` bash
root$:python main.py
```
![](https://github.com/LiodAir/Cnvdspider/blob/master/images/run.png)

![](https://github.com/LiodAir/Cnvdspider/blob/master/images/runa.png)

![](https://github.com/LiodAir/Cnvdspider/blob/master/images/hah.png)


