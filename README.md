# 产品看板（私人）

单页看板，数据以 AES-256-GCM 加密内嵌，需访问口令才能解密查看。

- 访问：GitHub Pages 地址 + 口令
- 更新：本地运行 `node build_publish.js <口令>` 重新生成 `dist/index.html` 后推送
- 说明：本仓库只存放加密后的数据，无口令看到的是一串密文
