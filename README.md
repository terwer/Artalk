# Artalk
self hosted comment system

# 注意mysql数据库编码

```
ALTER DATABASE dbname CHARACTER SET utf8 COLLATE utf8_general_ci;
```

## Using aliyun private image repo

```bash
docker pull artalk/artalk-go:2.9.1 
docker images
docker tag 5aac21791b04 registry.cn-shenzhen.aliyuncs.com/terwer/dm:artalk-go-2.9.1
docker login --username=terwer@aliyun.com registry.cn-shenzhen.aliyuncs.com
docker push registry.cn-shenzhen.aliyuncs.com/terwer/dm:artalk-go-2.9.1
```