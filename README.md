# dsh-theme-xuanzhi（宋律 · 定制）

DeepSeek Harness 的浅色主题插件，完全本地化、不再依赖上游加载；历史基于「宋律 Songgrid」定制，现为单文件本地主题「宋律 · 定制」。

## 上游与版权

- 上游项目：**dsh-theme-songgrid** v0.1.7 — https://github.com/yefengliu1/dsh-theme-songgrid
- 作者：**yefengliu1**；许可证：**MIT**
- 本仓库是个人定制备份，非官方发布。原主题的设计与代码版权归原作者所有；本仓库只移除「夜墨」深色变体并做少量样式调整，继续沿用 MIT 许可证（见 `LICENSE`）。

## 改动概要（相对上游）

- 左侧栏更紧凑：行高与分组间距收紧
- 正文 / 输入框宽度调整（900px）
- 强调色统一：链接群青、加粗与列表标记赭石、状态色朱砂
- 代码框标题栏与底色微调

## 安装（DSH 桌面）

1. 把本目录放到 profile 的依赖里：`pnpm add file:./dsh-theme-xuanzhi`（或复制到 profile 的 `node_modules`）
2. 在 profile `package.json` 的 `dsh.profile.bundles` 中加入 `dsh-theme-xuanzhi`
3. 重载 / 重启 DSH，在「设置 → 通用 → 主题」选择 **宋律 · 宣纸**

## 说明

仅保留浅色「宣纸」；原「宋律 · 夜墨」深色变体已删除，旧选择会自动回落到宣纸。
