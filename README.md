# 通用夜间模式切换器（UserScript）

## 简介

本脚本为一款适用于任意网页的夜间模式切换器，采用 CSS filter 降低亮度的方式实现夜间模式，不破坏原有网页样式。支持按钮拖动、位置记忆、快捷键切换（Ctrl+Shift+D 或 Cmd+Shift+D），并兼容 SPA 页面。

## 功能特性
- 一键切换夜间/日间模式，亮度调节不影响原网页结构
- 支持按钮拖动，自动记忆按钮位置
- 支持快捷键切换（Ctrl+Shift+D 或 Cmd+Shift+D）
- 兼容大多数现代浏览器和 SPA 应用
- 滚动条夜间样式优化，兼容 Chrome/Safari/Edge/Firefox
- 轻量级实现，性能友好

## 使用方法
1. 安装 [Tampermonkey](https://www.tampermonkey.net/) 或 [Violentmonkey](https://violentmonkey.github.io/) 等用户脚本管理器。
2. 新建脚本，将 `dark-mode-userscript.js` 文件内容粘贴进去并保存。
3. 脚本会自动在所有网页生效，右下角会出现夜间模式切换按钮。
4. 可拖动按钮调整位置，刷新后自动记忆。
5. 可使用快捷键 Ctrl+Shift+D（Windows）或 Cmd+Shift+D（Mac）快速切换夜间模式。

## 参数说明
- `filterValue`：夜间模式亮度（默认 0.5，可自行调整）
- `buttonSize`：切换按钮尺寸（默认 48px）
- 其它参数详见脚本内 `CONFIG` 配置项

## 兼容性
- 支持主流桌面浏览器（Chrome、Edge、Safari、Firefox 等）
- 支持大部分移动端浏览器（但拖动体验可能略有差异）

## 注意事项
- 本脚本通过 filter 降低亮度实现夜间模式，部分极端配色网页可能效果有限
- 若遇到兼容性问题或建议，欢迎反馈

