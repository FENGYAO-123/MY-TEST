---
title: "Notebook Navigator - Obsidian 现代文件资源管理器"
description: "通过双窗格导航、丰富预览和强大的组织功能，改变您的 Obsidian 工作流程。"

menu:
  nav:
    - title: "首页"
      url: ""
      weight: 1
    - title: "文档"
      url: "zh/docs.html"
      weight: 2
    - title: "支持"
      url: "#support"
      weight: 3
  footer:
    产品:
      - title: "功能特性"
        url: "#features"
      - title: "产品展示"
        url: "#showcase"
      - title: "安装指南"
        url: "#installation"
      - title: "更新日志"
        url: "https://github.com/johansan/notebook-navigator/releases"
    资源:
      - title: "文档"
        url: "docs.html"
      - title: "API 参考"
        url: "https://github.com/johansan/notebook-navigator/blob/main/docs/api-reference.md"
      - title: "主题指南"
        url: "https://github.com/johansan/notebook-navigator/blob/main/docs/theming-guide.md"
      - title: "技术支持"
        url: "https://github.com/johansan/notebook-navigator/issues"
    社区:
      - title: "Discord 服务器"
        url: "https://discord.gg/6eeSUvzEJr"
      - title: "Obsidian 论坛"
        url: "https://obsidian.md/community"
      - title: "Reddit 社区"
        url: "https://www.reddit.com/r/ObsidianMD/"
      - title: "GitHub 主页"
        url: "https://github.com/johansan"

organization:
  name: "Notebook Navigator"
  description: "Obsidian 现代文件资源管理器"
  vision: "让 Obsidian 导航变得直观而强大"
  website: "https://notebooknavigator.com"
  logo: "/images/favicon.svg"
  contact:
    email: "hello@notebooknavigator.com"
    address: "全球远程"
  social:
    github: "https://github.com/johansan/notebook-navigator"
    discord: "https://discord.gg/6eeSUvzEJr"
    linkedin: "https://linkedin.com/in/johan-sanneblad"
    twitter: "https://twitter.com/johan_sanneblad"
---

{{< hero 
    title="<span class=\"text-gradient\">Obsidian</span> 现代文件资源管理器"
    subtitle="完整键盘导航。双窗格布局。移动端优化。支持 100,000+ 笔记。永久免费。"
    image="hero-preview.png" 
>}}

{{< hero-action text="在 Obsidian 中安装" url="obsidian://show-plugin?id=notebook-navigator" class="btn-primary" icon="download" />}}

{{< hero-action text="查看文档" url="docs.html" class="btn-secondary" />}}

{{< hero-stat value="免费" label="开源软件" />}}
{{< hero-obsidian label="下载量" plugin="notebook-navigator" fallback="51k" />}}
{{< hero-github label="GitHub 星标" repo="johansan/notebook-navigator" fallback="431" />}}

{{< /hero >}}

{{% releases 
    label="最新更新"
    title="最新版本"
    subtitle="如果您有改进建议，请在我们的 GitHub 上提交问题"
    github="johansan/notebook-navigator"
%}}

在 [GitHub](https://github.com/johansan/notebook-navigator/releases) 上查看最新版本

{{% /releases %}}

{{< features 
    label="功能特性"
    title="终于，让 Obsidian 有了家的感觉"
    subtitle="Apple Notes 的速度。Bear 的美观。Evernote 的效率。Obsidian 的可扩展性。"
    image="hero-preview.png"
>}}

{{< feature 
    title="键盘导航" 
    icon="keyboard"
>}}
方向键、Tab 键切换窗格、Page Up/Down、Home/End。Shift+↑/↓ 扩展选择。
{{< /feature >}}

{{< feature 
    title="双窗格布局" 
    icon="dual-pane"
>}}
左侧导航，右侧文件。可调整分隔线。自动显示活动文件。面包屑导航。
{{< /feature >}}

{{< feature 
    title="固定和整理" 
    icon="star"
>}}
将笔记固定到顶部。带可点击链接的文件夹笔记。自定义 Lucide 图标、表情符号和颜色。
{{< /feature >}}

{{< feature 
    title="分层标签" 
    icon="tag"
>}}
父子标签树。拖拽添加标签或移至未标记。收藏标签区域。按层级隐藏标签。
{{< /feature >}}

{{< feature 
    title="丰富预览" 
    icon="preview"
>}}
1-5 行预览。来自 frontmatter 的特色图片。日期分组。可点击标签。每个文件夹自定义。
{{< /feature >}}

{{< feature 
    title="闪电般快速" 
    icon="lightning"
>}}
支持 100,000+ 笔记。React + TanStack Virtual。IndexedDB + RAM 缓存。批处理引擎。
{{< /feature >}}

{{< feature 
    title="移动端优化" 
    icon="mobile"
>}}
触控友好按钮。单窗格模式。可滚动面包屑。支持 Android、iOS、iPadOS。
{{< /feature >}}

{{< feature 
    title="快速搜索" 
    icon="search"
>}}
当前文件夹即时筛选。导航到文件夹/标签命令。
{{< /feature >}}

{{< feature 
    title="多选功能" 
    icon="copy"
>}}
Cmd/Ctrl+点击切换。Shift+点击范围选择。Cmd/Ctrl+A 全选。所有操作支持批处理。
{{< /feature >}}

{{< feature 
    title="Frontmatter 支持" 
    icon="file"
>}}
自定义笔记名称、日期、预览文本。通过属性隐藏笔记。文件夹笔记自动属性。
{{< /feature >}}

{{< feature 
    title="开发者 API" 
    icon="code"
>}}
TypeScript API。元数据控制。导航和选择。事件订阅。
{{< /feature >}}

{{< feature 
    title="高级主题" 
    icon="palette"
>}}
80+ CSS 变量。支持 Style Settings 插件。完整主题文档。
{{< /feature >}}

{{< /features >}}

{{< showcase 
    label="产品展示"
    title="实际效果演示"
>}}

{{% showcase-item 
    title="双窗格界面"
    image="detail-dual-pane.png"
%}}

左侧导航树，右侧文件列表。拖拽调整大小。键盘 Tab 键切换窗格。

- 文件夹笔记 - 文件夹变成带关联笔记的可点击链接
- 显示子文件夹笔记 - 一次性查看所有子文件夹笔记
- 自动显示活动文件，支持展开和滚动
- 每个文件夹/标签的自定义排序和外观设置

{{% /showcase-item %}}

{{% showcase-item 
    title="标签管理"
    image="detail-tags.png"
%}}

分层标签如 #项目/工作/紧急。拖拽即时添加/移除标签。

- 收藏标签 - 将常用标签固定到专用区域
- 拖拽到"未标记"以移除笔记的所有标签
- 基于层级的隐藏标签（例如，隐藏"存档"会隐藏"存档/2024"等）
- 上下文菜单进行精确标签操作

{{% /showcase-item %}}

{{% showcase-item 
    title="丰富的笔记预览"
    image="detail-preview.png"
%}}

可配置 1-5 行预览文本。使用特色图片插件自动生成缩略图。

- 来自 frontmatter 或第一个嵌入图片的特色图片
- 日期分组 - 今天、昨天、本周、上周
- 带自定义颜色的可点击标签，便于视觉组织
- 精简模式 - 需要时的紧凑视图，无预览

{{% /showcase-item %}}

{{< /showcase >}}

{{< installation 
    label="安装指南"
    title="几秒钟即可开始使用"
    plugin="Notebook Navigator"
>}}

{{< install-action text="在 Obsidian 中安装" url="obsidian://show-plugin?id=notebook-navigator" class="btn-primary" icon="download" />}}

{{< install-action text="查看文档" url="docs.html" class="btn-secondary" />}}

{{< /installation >}}

{{< about 
    label="关于"
    title="由行业资深人士打造"
    name="Johan Sanneblad, PhD"
    subtitle="编程热情"
>}}

{{% creator-bio %}}

拥有软件开发博士学位，并在 Apple、Electronic Arts、Google、Microsoft、LEGO 和沃尔沃汽车等公司拥有数十年产品开发经验的我，一年前决定看看能否突破用户对现代笔记应用的期望界限。经过六个月的规划和另外六个月的密集开发，Notebook Navigator 终于准备好全球发布了。

目前大多数笔记应用如 Apple Notes、Bear 和 Evernote 似乎都困在旧的遗留框架和复杂架构中，使得它们几乎无法创新新功能。是时候创建一个全新的最先进的笔记体验了，从头开始构建，专注于可扩展性、性能和用户体验。这是一个可以持续构建数年，甚至数十年的产品。

当您使用 Notebook Navigator 时，我希望您能体验到在当今科技行业中已经变得非常罕见的东西：设计如此完善的软件，感觉就像是您大脑的自然延伸。这正是 Notebook Navigator 给我的感觉，这也是我构建它的原因。

如果您有功能建议，请在我们的 [wiki](https://github.com/johansan/notebook-navigator/wiki) 中发布。如果您只是想打个招呼，非常欢迎加入我们的 [Discord 服务器](https://discord.gg/6eeSUvzEJr)！

{{% /creator-bio %}}

{{< creator-links >}}
{{< about-link text="在 LinkedIn 上联系" url="https://www.linkedin.com/in/johansan/" icon="linkedin" />}}
{{< about-link text="在 GitHub 上关注" url="https://github.com/johansan" icon="github" />}}
{{< /creator-links >}}

{{< /about >}}

{{< support 
    title="支持项目"
    description="Notebook Navigator 是免费开源的。如果您喜欢使用它，请考虑支持开发。"
>}}

{{< support-action text="在 GitHub 上赞助" url="https://github.com/sponsors/johansan" class="btn-primary" icon="heart" />}}
{{< support-action text="请我喝杯咖啡" url="https://www.buymeacoffee.com/johansan" image="default-yellow.png" target="_blank" />}}
{{< /support >}}