# Pandoc Web

基于 pandoc/typst 的 Typst 编辑器，支持实时预览、图片管理和多格式导出。

## 功能

- 创建 / 上传 / 编辑 `.typ` 文件，Typst 语法高亮
- 编辑时右侧实时预览（pandoc typst → HTML），支持 `#include`/`#import` 展开
- 图片管理：上传截图，在编辑器中一键插入引用
- 一键编译下载：PDF / EPUB / HTML / DOCX / Markdown / LaTeX

## 快速开始

```bash
docker compose up --build
```

访问 `http://localhost:5000`。

## 插入图片

1. 切换到侧栏"图片"Tab
2. 点击 ↑ 上传截图（PNG / JPG / SVG / PDF）
3. 点击图片名，自动在编辑器中插入引用代码
4. 修改 `图片说明` 为实际内容即可
