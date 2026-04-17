# my_docs
自己造轮子是一件苦差事，借助 `vuepress-theme-plume` 生成自己的文档网站

先安装 `node.js`，再安装 `pnpm`

```
npm install -g pnpm@latest-10
```
或
```
winget install -e --id pnpm.pnpm
```

开始安装
```
pnpm create vuepress-theme-plume@latest
```

安装依赖
```
pnpm i
```

启动程序
```
pnpm run docs:dev
```

生产构建
```
pnpm run docs:build
```

主题更新
```
pnpm dlx vp-update
```