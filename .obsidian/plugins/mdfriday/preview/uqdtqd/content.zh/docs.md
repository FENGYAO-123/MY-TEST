---
title: "文档"
description: "Notebook Navigator 完整文档 - Obsidian 现代文件资源管理器"
---

# Notebook Navigator 文档

欢迎查看 Notebook Navigator 的完整文档，这是一个为 Obsidian 设计的现代文件资源管理器。

## 开始使用

### 安装

1. 在 Obsidian 中打开设置 → 社区插件
2. 搜索 "Notebook Navigator"
3. 点击安装，然后启用
4. 插件将出现在您的左侧边栏中

### 第一步

安装后，Notebook Navigator 将用功能强大的双窗格界面替换您的默认文件资源管理器，具有以下特性：

- **导航树** 位于左侧
- **文件列表** 位于右侧
- 窗格间的**可调整分隔线**
- 每个笔记的**丰富预览文本**

## 主要功能

### 键盘导航

通过完整的键盘支持来导航您的知识库：

- **方向键** - 在列表中上下移动
- **Tab 键** - 在窗格间切换
- **Page Up/Down** - 按页跳转
- **Home/End** - 跳转到开始/结束
- **Shift + ↑/↓** - 扩展选择

### 双窗格布局

界面分为两个主要区域：

1. **导航窗格**（左侧）
   - 文件夹树结构
   - 标签层次结构
   - 固定笔记区域

2. **文件列表窗格**（右侧）
   - 选定文件夹/标签中的文件
   - 带缩略图的丰富预览
   - 日期分组选项

### 丰富预览

每个笔记显示：

- **预览文本**（可配置 1-5 行）
- 来自 frontmatter 的**特色图片**
- **创建/修改日期**
- 带颜色的**可点击标签**
- **文件大小**和字数统计

## 开发者 API

Notebook Navigator 为插件开发者提供了 TypeScript API：

### 基本用法

```typescript
// 获取插件实例
const nbNav = this.app.plugins.plugins['notebook-navigator'];

// 访问 API
const api = nbNav.api;

// 导航到文件夹
api.navigateToFolder('path/to/folder');

// 获取选定的文件
const selected = api.getSelectedFiles();

// 订阅事件
api.on('selection-changed', (files) => {
    console.log('Selected files:', files);
});
```

### 可用方法

- `navigateToFolder(path: string)` - 导航到文件夹
- `navigateToTag(tag: string)` - 导航到标签
- `getSelectedFiles()` - 获取当前选定的文件
- `selectFiles(paths: string[])` - 选择特定文件
- `refreshView()` - 刷新当前视图

### 事件

- `selection-changed` - 选择更改时触发
- `navigation-changed` - 导航更改时触发
- `view-refreshed` - 视图刷新后触发

## 许可证

Notebook Navigator 基于 MIT 许可证发布。详细信息请参阅 [LICENSE](https://github.com/johansan/notebook-navigator/blob/main/LICENSE) 文件。

---

**需要更多帮助？** 请查看我们的 [GitHub 仓库](https://github.com/johansan/notebook-navigator) 或加入 Obsidian Discord 服务器的讨论。
