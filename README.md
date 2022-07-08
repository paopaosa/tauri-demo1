# Vue 3 + TypeScript + Vite

This template should help get you started developing with Vue 3 and TypeScript in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar)

## Type Support For `.vue` Imports in TS

Since TypeScript cannot handle type information for `.vue` imports, they are shimmed to be a generic Vue component type by default. In most cases this is fine if you don't really care about component prop types outside of templates. However, if you wish to get actual prop types in `.vue` imports (for example to get props validation when using manual `h(...)` calls), you can enable Volar's Take Over mode by following these steps:

1. Run `Extensions: Show Built-in Extensions` from VS Code's command palette, look for `TypeScript and JavaScript Language Features`, then right click and select `Disable (Workspace)`. By default, Take Over mode will enable itself if the default TypeScript extension is disabled.
2. Reload the VS Code window by running `Developer: Reload Window` from the command palette.

You can learn more about Take Over mode [here](https://github.com/johnsoncodehk/volar/discussions/471).

# 日志

学习一个跨平台的桌面开发套件 Tauri


## 2022年07月08日 12:50:06

[Tauri](https://youtu.be/-X8evddpu7M)看起来，打包出来的体积非常地小，值得一试。

目前测试了, 以下平台：

- macOS 
- Arm Windows 11 
- Debian 10

都没有什么大问题。图标更换tauricon在 Arm Win11 上有些问题。

接下来查看一下 [Vue](https://vuejs.org/api/sfc-script-setup.html) 部分的开发，以及 [Rust基础的学习](https://doc.rust-lang.org/book/)。

