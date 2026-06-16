# cczzqqyy999-site

这是 `https://cczzqqyy999.me/` 的静态网站源码，当前通过 GitHub Pages 部署。

## 当前状态

- 首页：`index.html`
- 自定义域名：`CNAME`
- 搜索引擎入口：`robots.txt`、`sitemap.xml`
- GitHub Pages 配置：`.nojekyll`
- 基础维护配置：`.editorconfig`、`.gitattributes`、`.gitignore`

## 本地预览

这个项目目前是纯静态页面，可以直接打开 `index.html` 预览。

也可以在项目目录运行一个本地静态服务器：

```bash
python -m http.server 8080
```

然后访问：

```text
http://localhost:8080/
```

## 发布

把修改推送到 GitHub 仓库的默认分支后，GitHub Pages 会自动更新线上网站。

域名配置文件 `CNAME` 需要保留，内容为：

```text
cczzqqyy999.me
```
