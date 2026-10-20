# ainative-publish

AI Native Engine × AI Rendering 日报的**发布仓库**。

- `feed.xml` —— RSS 2.0 订阅源（全文 + 配图），每天由 `../ainative-feed/publish.py` 覆盖更新
- `index.html` —— 浏览器可读的当日列表
- `.nojekyll` —— 关掉 Jekyll，保证 XML 原样输出

## 订阅地址

```
https://peasmallhui.github.io/ainative-publish/feed.xml
```

浏览器看首页：

```
https://peasmallhui.github.io/ainative-publish/
```

## 更新方式

```bat
python E:\_hui\xd_dev\ainative-feed\publish.py
```

代码在 `../ainative-feed/`，本仓库只放产物，避免工作仓库被每日提交撑大。

## 部署

GitHub Pages：Settings → Pages → Deploy from a branch → `main` / `(root)`。
推送后约 1 分钟自动生效。
