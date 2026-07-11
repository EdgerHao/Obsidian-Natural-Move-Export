# Natural Move/Export 1.0.10

## 修复

- 修复从 macOS Finder 复制文件后，插件提示“系统剪贴板中没有可粘贴的外部文件或文件夹”的问题。
- 使用原生 `NSArray` 和 `NSDictionary` 类型调用 `NSPasteboard`，确保 Finder 文件 URL 能被正确读取。

## 使用方法

在 Finder 中复制文件或文件夹，然后右键单击 Obsidian 文件夹，选择“Natural move: 粘贴外部文件到此处”。

## BRAT Release 附件

请将 `main.js`、`manifest.json`、`styles.css` 作为三个独立附件上传。ZIP 文件可作为额外下载包，但不能替代这三个 BRAT 附件。
