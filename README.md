# miscada-orthanc

## 项目简介
miscada-orthanc 是一个用于集成 Orthanc 医学影像服务器的服务组件，支持通过 Docker Compose 快速部署和配置。该项目旨在为医学影像数据的存储、管理和访问提供便捷的解决方案。

## 目录结构
- config/：Orthanc 配置文件
- logs/：日志文件目录
- volumes/：数据持久化存储目录
- docker-compose.yml：一键部署配置文件

## 快速开始

1. 克隆本仓库：
   ```sh
   git clone <your-repo-url>
   cd miscada-orthanc
   ```

2. 启动服务：
   ```sh
   docker-compose up -d
   ```

3. 访问 Orthanc Web 界面：
   ```
   http://localhost:8042
   ```

