# PsdSmartCleaner-PSD-智能清理冗余数据
# Photoshop 智能清理脚本

## 简介

该脚本旨在自动清理 Photoshop PSD 文件中的不必要元素，如空图层、隐藏图层和重复图层，帮助用户优化文件结构，减少文件大小，提高工作效率。

## 功能

- **清理空图层**：自动删除所有空白图层。
- **删除隐藏图层**：移除所有不可见的图层。
- **合并重复图层**：识别并合并具有相同内容的图层。
- **批量处理**：支持一次性处理多个 PSD 文件。

## 安装

1. **下载脚本文件**：从 [GitHub 仓库](https://github.com/wsdpsy/psd-smart-cleaner) 下载 `PsdSmartCleaner-V4.6_智能清理-beta.jsx` 文件。
2. **放置脚本文件**：将下载的 `.jsx` 文件放入 Photoshop 的脚本文件夹中。
   - **Windows**：`C:\Program Files\Adobe\Adobe Photoshop [版本号]\Presets\Scripts\`
   - **macOS**：`/Applications/Adobe Photoshop [版本号]/Presets/Scripts/`
3. **重启 Photoshop**：关闭并重新打开 Photoshop，以加载新脚本。

## 使用方法

1. **打开 PSD 文件**：在 Photoshop 中打开需要清理的 PSD 文件。
2. **运行脚本**：依次点击菜单栏的“文件” > “脚本” > “PsdSmartCleaner-V4.6_智能清理-beta”。
3. **选择清理选项**：在弹出的对话框中，勾选需要执行的清理操作，如清理空图层、删除隐藏图层等。
4. **开始清理**：点击“开始清理”按钮，脚本将自动执行所选操作。

## 注意事项

- **备份文件**：在使用脚本前，建议备份原始 PSD 文件，以防止意外删除重要内容。
- **兼容性**：该脚本适用于 Photoshop CC 2025版本，其他版本可能无法正常运行。
- **批量处理**：对于批量处理多个文件，建议将文件放置在同一文件夹中，并在脚本设置中选择批量处理选项。

## 常见问题

**Q1：脚本运行后文件无响应，怎么办？**

A1：可能是由于 Photoshop 版本不兼容或脚本本身存在错误。请确保使用的是支持的 Photoshop 版本，并检查脚本文件是否完整。

**Q2：如何恢复被误删的图层？**

A2：建议在使用脚本前先备份文件，以防止误删。若未备份，可能需要手动恢复或使用 Photoshop 的历史记录功能。

## 贡献

欢迎提交问题报告、功能请求或代码贡献。请通过 GitHub 提交 [issue](https://github.com/your-repo/psd-smart-cleaner/issues) 或 [pull request](https://github.com/your-repo/psd-smart-cleaner/pulls)。

## 许可证

本项目采用 MIT 许可证，详情请参阅 [LICENSE](https://github.com/your-repo/psd-smart-cleaner/blob/master/LICENSE)。