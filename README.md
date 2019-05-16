# wlniao/sshd
一个开放SSH服务的容器镜像，可通过`PASSWORD`变量设置ROOT用户的密码。
```
docker run -d -p222:22 -e PASSWORD=123456 --name sshd wlniao/sshd
```