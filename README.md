# 地球（部署版）

静态站点，无需后端。上传整个文件夹即可。

## 本地预览
    node serve.mjs        →  http://127.0.0.1:8124/

## 部署
- Netlify Drop：https://app.netlify.com/drop ，把文件夹（或 earth-site.zip）拖进去，几秒后给一个 https 地址
- GitHub Pages：把全部文件推到仓库根目录，Settings → Pages → 选 main 分支根目录
- Cloudflare Pages：Direct Upload，拖文件夹

## 注意
- 贴图是压缩过的 4K/2K 版本（总共约 1.9 MB），适合手机流量；桌面想更清晰可以把 assets 换回 8K 版
- 必须有贴图文件，file:// 直接打开会被浏览器拦住（页面会提示）