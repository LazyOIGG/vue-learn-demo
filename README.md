# Vue Learn Demo

## 项目简介
这是一个 Vue 3 学习项目，用于实践和掌握 Vue 相关技术栈。

## 技术栈
- Vue 3
- TypeScript
- Vite
- UnoCSS

## 项目结构
```
vue-learn-demo/
├── public/              # 静态资源
│   └── assets/
│       ├── icons/       # 图标资源
│       └── images/      # 图片资源
├── src/
│   ├── assets/          # 项目资源
│   │   ├── main.css     # 主样式文件
│   │   └── styles.css   # 样式文件
│   ├── App.vue          # 根组件
│   └── main.ts          # 应用入口
├── .gitignore           # Git忽略配置
├── index.html           # 主HTML文件
├── package.json         # 项目配置
├── vite.config.ts       # Vite配置
└── uno.config.ts        # UnoCSS配置
```

## 快速开始

### 安装依赖
```bash
pnpm install
```

### 开发模式
```bash
pnpm dev
```

### 生产构建
```bash
pnpm build
```

### 预览生产版本
```bash
pnpm preview
```

## 注意事项
- 项目使用 pnpm 作为包管理器
- 开发时请确保 Node.js 版本 >= 16.0.0
- 主要样式使用 UnoCSS 处理

Happy Coding! 🚀