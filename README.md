# example-dock

基于 Docker Compose 搭建的example服务环境

# IP地址
内部IP地址从 172.25.100.3 开始

# 服务清单

| status | service | backend ip | version | 备注 |
|---|---|---|---|---|
| &check; | whoami | 172.25.100.3 | latest | |

# 使用到的镜像
- 默认使用docker.io 镜像
- 若想使用自定义仓库镜像，需要定义 `DOCKER_REGISTRY_URL` 变量

```json
[
    "traefik/whoami:latest"
]
```
