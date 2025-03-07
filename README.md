# PsdSmartCleaner-PSD智能清理
# Photoshop 智能清理脚本

## 简介

该脚本旨在自动清理 Photoshop PSD 文件中的meta数据，和空图层、隐藏图层等，帮助用户优化文件结构，减少文件大小，提高工作效率。

## 功能

- **----基础清理选项----**
- **删除冗余数据**：清理当前文档的冗余数据，不做深入检索。//适用于快速清理，智能对象很多，以及已经清理过的文档。
- **删除空白图层**：自动删除当前文档的空白图层，不做深入检索。
- **清理临时文件**：删除temp目录下的文件，跳过报错的文件。//适应于C盘空间不足或者多次清理后，缓存文件太多。
- **----智能对象选项----**
- **智能对象深度清理**：自动深度检索智能对象，删除冗余数据。
- **清理智能空图层**：自动深度检索智能对象里的所有空白图层，并删除。
- **删除智能隐藏图层**：自动深度检索智能对象里的所有隐藏图层。（有破坏性，请做好备份）
- **栅格化智能**：
- **----创成式填充选项----**
- **跳过创成式填充**：Photoshop新版AI生成的图片。
- **栅格化创成式填充**：没有用到的生成就直接丢弃掉
- **转为图层beta**：把对象转成图层组，保留多个生成。//此功能的处理逻辑还未完善，暂时会报错，不过不影响使用。
- **----图片处理----**
- **图片转psd**：支持jpg、png、webp素材转成可以编辑的psd。//有时候做效果完才发现素材图片不可编辑，这个可以无痛转成psd，不过文件会变大。
- **图片转原始格式**：此选项一般用于批量处理的时候，减少弹窗中断的干扰。
- **----批量处理文件----**
- **批量处理**：支持一次性处理多个 PSD 文件。建议勾上**图片转原始格式**
- **----单文件恢复----**
- **恢复快照**：单文件处理支持恢复到之前的历史状态（恢复快照）
![image](https://github.com/user-attachments/assets/dde1954c-fa5d-4bcb-b79c-0d2345095b6a)

## 安装

1. **下载脚本文件**：从 [GitHub 仓库](https://github.com/wsdpsy/PsdSmartCleaner) 下载 `PSD智能清理_PsdSmartCleaner_V4.6.jsxbin` 文件。
2. **放置脚本文件**：将下载的 `.jsxbin` 文件放入 Photoshop 的脚本文件夹中。
   - **Windows**：`C:\Program Files\Adobe\Adobe Photoshop [版本号]\Presets\Scripts\`
   - **macOS**：`/Applications/Adobe Photoshop [版本号]/Presets/Scripts/`
3. **重启 Photoshop**：关闭并重新打开 Photoshop，以加载新脚本。

## 使用方法

1. **打开 PSD 文件**：在 Photoshop 中打开需要清理的 PSD 文件。
2. **运行脚本**：依次点击菜单栏的“文件” > “脚本” > “PSD智能清理_PsdSmartCleaner_V4.6”。
3. **选择清理选项**：在弹出的对话框中，勾选需要执行的清理操作，如清理空图层、删除隐藏图层等。
4. **开始清理**：点击“开始清理”按钮，脚本将自动执行所选操作。

## 注意事项

- **备份文件**：在使用脚本前，建议备份原始 PSD 文件，以防止意外删除重要内容。
- **兼容性**：该脚本适用于 Photoshop CC 2025版本，其他版本可能无法正常运行，大概率兼容CC 2019以上。
- **批量处理**：对于批量处理多个文件，建议将文件放置在同一文件夹中，并在脚本设置中选择批量处理选项。

## 常见问题

**Q1：脚本运行后文件无响应，怎么办？**

A1：可能是由于 Photoshop 版本不兼容或脚本本身存在错误。请确保使用的是支持的 Photoshop 版本，并检查脚本文件是否完整。

**Q2：如何恢复被误删的图层？**

A2：建议在使用脚本前先备份文件，以防止误删。若未备份，可能需要手动恢复或使用 Photoshop 的历史记录功能。

