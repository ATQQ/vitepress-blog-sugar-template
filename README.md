# vitepress @sugarat/theme example

<p align="center">
简约风的 <a href="https://theme.sugarat.top"  target="_blank"target="_blank">Vitepress 博客主题</a> 示例运行项目。
</p>

<p align="center">
    <a href="https://atqq.github.io/vitepress-blog-sugar-template/" target="_blank">GitHub Pages Demo</a>
</p>

## Github Pages 部署

① 复制文件到自己的项目 `.github/workflows/deploy.yml`

② 修改 `docs/.vitepress/config.mts` 里的构建配置

`base` 改为 `"/仓库名/"` 即可

## Gitee Pages 部署

① 参照[文档](https://help.gitee.com/services/gitee-pages/intro)推送构建后的页面资源到部署分支

② 按照 [SPA](https://help.gitee.com/services/gitee-pages/spa-support) 要求添加 `.spa` 文件在`docs/public` 目录下

## Usage

先安装 `pnpm`

```sh
npm i -g pnpm
```

安装依赖

```sh
pnpm install
```

开发启动

```sh
pnpm dev
```

构建

```sh
pnpm build
```

预览产物

```sh
pnpm serve
```
