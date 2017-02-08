CentOS安装nginx
---

> 下载nginx包

```
 wget  http://nginx.org/packages/centos/7/noarch/RPMS/nginx-release-centos-7-0.el7.ngx.noarch.rpm
```

> 建立nginx的yum仓库

```
 rpm -ivh nginx-release-centos-7-0.el7.ngx.noarch.rpm
```

> 安装nginx

```
yum install nginx
```

> 启动nginx服务

```
systemctl start nginx
```

> 配置
>
>默认的配置文件在 /etc/nginx 路径下，使用该配置已经可以正确地运行nginx；如需要自定义，修改其下的 nginx.conf 等文件即可

> 测试
>
> 在浏览器地址栏中输入部署nginx环境的机器的IP

