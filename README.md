# 镜像仓库使用方法

[**images.txt**](https://github.com/fuzhengwei/docker-image-pusher/blob/main/images.txt)

```javascript
redis:6.2
redis-commander:0.8.0
nginx:1.25.1
prometheus:2.47.2
logstash:7.14.2
registry:latest
portainer:latest
```

1. 在 `images.txt` 添加你需要的镜像（PR方式提交），你可以从 [https://hub.docker.com/](https://hub.docker.com/) 搜索需要的镜像后添加。
2. 新添加镜像，需要等待1分钟同步。之后通过命令 `docker pull ip:port/image_name` 拉取你需要的镜像，如果有版本号，可以添加。如；`mysql:8.0.32`

---

- 参考仓库 [@tech-shrimp/docker_image_pusher](https://github.com/tech-shrimp/docker_image_pusher)
