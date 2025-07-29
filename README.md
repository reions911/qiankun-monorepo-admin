# qiankun-monorepo-admin

## 介绍
qiankun-monorepo-admin 是一个基于React Hooks、Umi、Vite和Typescript的中后台解决方案。它旨在帮助您快速搭建企业级中后台项目。

## 项目结构

```
react-antd-admin
├── TODO.md                                # TODO 列表
├── package.json                           # 项目依赖
├── pnpm-lock.yaml
├── packages                               # 多个项目
│   ├── main                               # 主项目，基于umi4构建
│   ├── sub-app-1                          #  子项目
│   ├── sub-app-2
│   ├── sub-app-3
│   └── sub-app-4
└── pnpm-workspace.yaml                    # pnpm 工作区配置
```

## 开发

### 安装依赖
```bash
npm install -g pnpm

pnpm i
```
### 运行
```bash
pnpm dev
```

打开浏览器输入 [http://localhost:5000](http://localhost:5000) 即可看到页面。


## 最后

欢迎交流, 如果本项目对你有帮助的话, 欢迎━(*｀∀´*)ノ亻!  ⭐⭐⭐ ~
