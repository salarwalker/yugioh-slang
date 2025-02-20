# 游戏王黑话文档

```
bun install
```

```
bun dev
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/ColinWttt/yugioh-slang/tree/main)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/ColinWttt/yugioh-slang/tree/main)

## 🚀 项目结构

文件夹和文件:

```
.
├── public/
├── src/
│   ├── assets/
│   ├── content/
│   │   ├── docs/
│   │   └── config.ts
│   └── env.d.ts
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

每个在 `src/content/docs/` 目录的`.md` 或 `.mdx` 文件都根据其文件名暴露为一个路由。

图片可以添加到 `src/assets/` ，并通过相对链接嵌入到 Markdown 中。

## 🧞 执行命令

所有命令都是从项目的根目录，在终端中运行的：:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `bun install`             | 安装依赖包                                         |
| `bun dev`                 | 在 `localhost:4322` 上启动本地开发服务器             |
| `bun run build`           | 将您的生产站点构建到 `./dist/` 目录下                 |
| `bun run preview`         | 在部署之前在本地预览您的构建     |

## 关于Starlight框架

请查看 [Starlight’s docs](https://starlight.astro.build/), 阅读 [the Astro documentation](https://docs.astro.build), 或加入 [Astro Discord server](https://astro.build/chat).
