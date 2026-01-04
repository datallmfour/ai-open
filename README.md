# AI Open WebUI Mirror

这是一个自动同步的镜像仓库，源自 [open-webui/open-webui](https://github.com/open-webui/open-webui)。

该仓库每天自动拉取官方最新 `main` 分支镜像，并支持全架构（AMD64/ARM64）。

### 🚀 快速使用

```bash
docker run -d -p 3000:8080 \
  --add-host=host.docker.internal:host-gateway \
  -v open-webui:/app/backend/data \
  --name open-webui \
  --restart always \
  ghcr.io/datallmfour/ai-open:latest
```

### 📊 同步状态

- **源镜像**: `ghcr.io/open-webui/open-webui:main`
- **上次同步时间 (北京时间)**: `2026-01-04 11:30:43`
- **同步状态**: ✅ 成功
- **架构支持**: `linux/amd64`, `linux/arm64` 等

> 此文件由 GitHub Actions 每日自动生成，以保持仓库活跃。
