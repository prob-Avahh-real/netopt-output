# netopt_output

Web 与网关全链路网络性能优化配置模板包（已归档于 `archive/from-home/netopt_output`）。

## 包含产物

- `nginx-gzip.conf`：Gzip / Brotli 传输压缩配置片段
- `nginx-cache.conf`：`Cache-Control` 与 `ETag` 静态资源缓存策略
- `nginx-http2.conf`：HTTP/2 + TLS 1.3 + KeepAlive 服务端配置模板
- `cloudflare.json`：CDN 边缘缓存、Tiered Cache 与路由参考配置
- `html-hints.html`：前端 `<head>` 的 `dns-prefetch` / `preload` 注入片段
- `CHECKLIST.md`：运维与前端上线核对清单及基准对比步骤

## 目标平台（Target 判定）

- **移动端**：可选（网关与 Web 传输配置产物）
- **智能硬件**：可选（可搁置）

## 验证命令

```bash
npm test
```

## 归档说明

由网络优化工具生成的基准配置归档目录，默认只做必要维护。
