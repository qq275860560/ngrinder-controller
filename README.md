[TOC]
ngrinder主节点

# 适用场景
适用于开发测试环境

# 功能
## ngrinder控制器


# 使用方式
## 安装

```
docker pull qq275860560/ngrinder-controller
```

## 启动
 
```
docker run -d  -p 80:80 -p 16001:16001 -p 12000-12009:12000-12009 \
-v /tmp:/tmp \
-e NGRINDER_HOME=/tmp/ngrinder-controller \
--name ngrinder-controller \
--hostname ngrinder-controller \
qq275860560/ngrinder-controller \
/etc/rc.local 

```

# 温馨提醒

* 此项目将会长期维护，增加或改进实用的功能
* 右上角点击star，给我继续前进的动力,谢谢