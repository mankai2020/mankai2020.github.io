# Kai Man · Personal Research Homepage

一个面向 GitHub Pages 的英文科研主页，集中介绍 Kai Man 作为第一作者发表的同行评议论文。

## 收录论文

- *Tropical oceans drive decadal trends in surface mass balance over Wilkes Land, East Antarctica* — Climate Dynamics (2026)
- *Uncertainty in Antarctic precipitation projections under global warming* — Environmental Research Letters (2026)
- *Century-long West Antarctic snow accumulation changes induced by tropical teleconnections* — Science Advances (2025)

这是一个不依赖框架或构建工具的静态页面。论文内容直接维护在 `index.html`，视觉样式位于 `styles.css`。

## 本地预览

```bash
python3 -m http.server 8000
```

访问 `http://localhost:8000`。

## GitHub Pages

`.github/workflows/pages.yml` 会在内容推送到 `main` 分支后自动部署主页。仓库的 **Settings → Pages → Source** 需要设置为 **GitHub Actions**。
