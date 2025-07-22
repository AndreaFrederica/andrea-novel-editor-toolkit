# Andrea Novel Editor

**VSCode 小说写作工具包**

## 简介

**Andrea Novel Editor** 集成了多款扩展，为小说创作提供从角色管理、文字编辑、Markdown 支持、项目管理到版本控制等一站式支持，帮助作者在 VSCode 中轻松完成创作全流程。

## 核心写作辅助

- **Andrea Novel Helper**  
  - 在项目根目录维护 JSON5 格式角色库  
  - 基于中文分词实现主名称与别名智能补全  
  - 编辑器中自动着色角色名／别名  
  - 悬停显示角色简介、类型、从属与颜色信息  
  - Ctrl/Cmd+Click 或 F12 跳转到角色库定义  
  - 右键选中快速创建新角色并追加到库  
  - 实时监控角色库改动或手动刷新角色列表 
  - 提供整卷的字数统计

- **实时字数统计**  
  - **holmescn.vscode-wordcount-cjk**：中英混合文字、CJK 字符与单词计数，实时跟踪章节长度。  

- **拼写与语法检查**  
  - **streetsidesoftware.code-spell-checker**：多语言拼写纠正，自动标记错别字和常见拼写错误。  

## Markdown 写作增强

- **yzhang.markdown-all-in-one**：目录生成、快捷键、表格编辑、折叠等一体化 Markdown 支持。  
- **shd101wyy.markdown-preview-enhanced**：支持公式、图表、幻灯片等高级预览。  
- **bierner.markdown-emoji** & **bierner.markdown-checkbox**：快速插入 Emoji 与任务列表。  
- **yzane.markdown-pdf**：一键导出 Markdown 为 PDF。  

## 项目与笔记管理

- **alefragnani.project-manager** & **felipecaputo.git-project-manager**：多项目快速切换，支持本地和 Git 仓库管理。  
- **alefragnani.bookmarks**：在长文档中添加书签，一键跳转至关键段落。  
- **gruntfuggly.todo-tree**：侧边栏展示 TODO/FIXME 注释，跟踪待办事项。  
- **gera2ld.markmap-vscode**：将 Markdown 大纲实时渲染为思维导图。  

## 版本控制

- **donjayamanne.git-extension-pack**, **eamodio.gitlens**, **donjayamanne.githistory**：Git 提交历史、分支视图、代码透视与时间轴。  
- **waderyan.gitblame**：行级作者归属与变更信息。  
- **shaharkazaz.git-merger**：可视化合并冲突辅助。  
- **ziyasal.vscode-open-in-github**：一键在浏览器打开 GitHub 仓库对应文件。  

## 编辑体验优化

- **aaron-bond.better-comments**：彩色注释分类，高亮提醒、疑问、提示等。  
- **anseki.vscode-color**：代码中颜色值可视化。  
- **christian-kohler.path-intellisense**：智能路径补全，快速插入图片、参考等链接。  
- **mkxml.vscode-filesize**：文件大小提示。  
- **pkief.material-icon-theme** & **ms-ceintl.vscode-language-pack-zh-hans**：美观图标与中文界面支持。  

## 格式化与配置

- **esbenp.prettier-vscode**：一键格式化 Markdown、JSON、TOML 等文件。  
- **tamasfe.even-better-toml**：TOML 语法高亮与智能感知。  
- **blueglassblock.better-json5** & **savh.json5-kit**：JSON5 语法增强与提示。  
- **codezombiech.gitignore**：快速生成常用 `.gitignore` 模板。  

## 错误提示与洞察

- **igorsbitnev.error-gutters** & **usernamehw.errorlens**：实时语法、格式或编译错误提示。  
- **jacquesgariepy.out-of-code-insights**：侧边栏文件统计与概览。  

## 安装

在 VSCode 扩展面板中搜索 **Andrea Novel Editor** 并安装，或在命令面板 (`Ctrl+P`) 输入：

```shell
ext install andrea-novel-editor
