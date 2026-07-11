# Natural Move/Export 1.0.11

## 新增

- 在 Obsidian 文件资源管理器中选中单个文件夹后，可直接按 `Command + V`（macOS）或 `Ctrl + V`（Windows/Linux）粘贴系统剪贴板中的文件和文件夹。
- 保留原有文件夹右键菜单粘贴入口。

## 优化

- 编辑器、输入框和多文件夹选择状态不会被插件拦截，继续使用 Obsidian 原生粘贴行为。
- 忽略按键长按产生的重复事件，防止同一批文件被多次导入。
- 同名项目继续自动追加序号，不会覆盖已有文件。

## BRAT Release 附件

请将 `main.js`、`manifest.json`、`styles.css` 作为三个独立附件上传。ZIP 文件可作为额外下载包，但不能替代这三个 BRAT 附件。
