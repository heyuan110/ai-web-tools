# AI Web Tools

> 一套纯前端的实用工具集，无需安装，浏览器直接打开即可使用。
>
> A collection of pure frontend utility tools. No installation required, just open in browser.

---

## 工具列表 / Tool List

| 文件 / File | 功能 / Function | 说明 / Description |
|-------------|-----------------|-------------------|
| `m3u8-downloader.html` | M3U8 视频下载器 | 批量下载 M3U8 视频，支持预览、暂停续传 |
| `json-viewer.html` | JSON 查看器 | 格式化显示 JSON，支持折叠展开、搜索 |
| `sqlite-viewer.html` | SQLite 查看器 | 浏览器内打开 SQLite 数据库，执行 SQL 查询 |

---

## 中文说明

### M3U8 视频下载器
批量下载 M3U8 流媒体视频并保存为本地文件。

**功能特点：**
- 单条或批量导入 M3U8 链接
- 实时视频预览（自动播放）
- 下载进度可视化
- 支持暂停/继续下载
- 批量保存已完成的视频

![M3U8 视频下载器](screenshots/m3u8-downloader.png)

### JSON 查看器
美观的 JSON 数据可视化工具。

**功能特点：**
- 语法高亮显示
- 节点折叠/展开
- 关键字搜索
- 支持粘贴或上传 JSON 文件

![JSON 查看器](screenshots/json-viewer.png)

### SQLite 查看器
在浏览器中直接查看和查询 SQLite 数据库。

**功能特点：**
- 拖拽上传 .db / .sqlite 文件
- 浏览所有表结构
- 执行自定义 SQL 查询
- 查询结果表格展示

![SQLite 查看器](screenshots/sqlite-viewer.png)

---

## English

### M3U8 Video Downloader
Batch download M3U8 streaming videos and save locally.

**Features:**
- Import single or multiple M3U8 URLs
- Real-time video preview (auto-play)
- Visual download progress
- Pause/Resume downloads
- Batch save completed videos

![M3U8 Video Downloader](screenshots/m3u8-downloader.png)

### JSON Viewer
Beautiful JSON data visualization tool.

**Features:**
- Syntax highlighting
- Collapsible nodes
- Keyword search
- Paste or upload JSON files

![JSON Viewer](screenshots/json-viewer.png)

### SQLite Viewer
View and query SQLite databases directly in browser.

**Features:**
- Drag & drop .db / .sqlite files
- Browse all table structures
- Execute custom SQL queries
- Display results in table format

![SQLite Viewer](screenshots/sqlite-viewer.png)

---

## 使用方法 / Usage

直接用浏览器打开对应的 HTML 文件即可：

Just open the HTML file in your browser:

```bash
open m3u8-downloader.html
open json-viewer.html
open sqlite-viewer.html
```

---

## 技术栈 / Tech Stack

- 纯 HTML + CSS + JavaScript
- 无需后端服务
- 依赖库：HLS.js (M3U8), sql.js (SQLite)

---

## License

MIT
