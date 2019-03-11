## **Kibana 6.x - Future 汉化项目**

> Kibana官方在6.x(具体版本忘了)的版本正式推出了资源汉化方法(虽然有很多资源还不能被汉化)，因此我废弃掉了之前暴力搜索替换的汉化方法。

> 老版本的汉化仍然可以参考此项目old文件下的汉化说明进行汉化，将来不再进行老版本汉化的维护(< 6.0)。

### 一、汉化方法

> 1、拷贝此项目中的translations文件夹到您的kibana目录下的src/legacy/core_plugins/kibana/目录。若您的kibana无此目录，那还是尝试使用此项目old目录下的汉化方法吧。

> 2、修改您的kibana配置文件kibana.yml中的配置项：i18n.locale: "zh_CN"

> 3、汉化完成

---

### 说明：

```
此方式汉化完整度依赖于官方在源代码中提供的汉化资源，所以些地方没有汉化我也是没有办法滴。
有问题请邮件联系：redfree#anbai.com (#=@)
```

> **如果您觉得此项目对您有用，不妨微信打赏作者一个小红包，您的支持是我前进最大的动力。**

![](https://github.com/anbai-inc/Kibana_Hanization/blob/master/images/wechat.png)


### 汉化效果：

![](https://github.com/anbai-inc/Kibana_Hanization/blob/master/images/kibana.png)

![](https://github.com/anbai-inc/Kibana_Hanization/blob/master/images/discover.png)
