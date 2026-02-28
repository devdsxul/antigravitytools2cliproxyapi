# antigravity tools ⇄ cliproxyapi

把 antigravity tools 和 cliproxyapi 两种 JSON 格式互转。纯前端，无后端依赖。

**在线使用：** https://antigravitytools2cliproxyapi.vercel.app/

## 使用

1. 浏览器打开 `index.html`
2. 拖入 JSON 文件（支持多文件 / 粘贴）
3. 自动识别格式并转换：
   - antigravity tools → cliproxyapi（每个账号一个文件）
   - cliproxyapi → antigravity tools（合并为一个账号列表）
4. 预览 / 单个下载 / 打包下载 ZIP

## 自动补全

转换 antigravity tools → cliproxyapi 时需要 `access_token` 和 `project_id`，工具会自动通过 `refresh_token` 联网获取。

## 文件命名

- antigravity tools 输出：`antigravity_accounts_YYYY-MM-DD.json`
- cliproxyapi 输出：`antigravity-<email>.json`
