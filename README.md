## Docker Images Dump

使用Github Action将国外的Docker镜像转存到阿里云私有仓库，供国内服务器使用，免费易用<br>
- 支持DockerHub, gcr.io, k8s.io, ghcr.io等任意仓库<br>
- 支持最大40GB的大型镜像<br>
- 使用阿里云的官方线路，速度快<br>

感谢：[技术爬爬虾](https://github.com/tech-shrimp)<br>

### 更新 ###
**2025-02-14**
新增：当拉取镜像失败时，会输出"镜像拉取失败，跳过当前镜像"并继续下一个镜像。
