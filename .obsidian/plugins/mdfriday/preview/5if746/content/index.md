---
title: "Notebook Navigator - Modern File Explorer for Obsidian"
description: "Transform your Obsidian workflow with dual-pane navigation, rich previews, and powerful organization features."

menu:
  nav:
    - title: "Home"
      url: ""
      weight: 1
    - title: "Documentation"
      url: "docs.html"
      weight: 2
    - title: "Support"
      url: "#support"
      weight: 3
  footer:
    product:
      - title: "Features"
        url: "#features"
      - title: "Showcase"
        url: "#showcase"
      - title: "Installation"
        url: "#installation"
      - title: "Changelog"
        url: "https://github.com/johansan/notebook-navigator/releases"
    resources:
      - title: "Documentation"
        url: "docs.html"
      - title: "API Reference"
        url: "https://github.com/johansan/notebook-navigator/blob/main/docs/api-reference.md"
      - title: "Theming Guide"
        url: "https://github.com/johansan/notebook-navigator/blob/main/docs/theming-guide.md"
      - title: "Support"
        url: "https://github.com/johansan/notebook-navigator/issues"
    community:
      - title: "Discord Server"
        url: "https://discord.gg/6eeSUvzEJr"
      - title: "Obsidian Forum"
        url: "https://obsidian.md/community"
      - title: "Reddit"
        url: "https://www.reddit.com/r/ObsidianMD/"
      - title: "GitHub Profile"
        url: "https://github.com/johansan"

organization:
  name: "Notebook Navigator"
  description: "Modern file explorer for Obsidian"
  vision: "Making Obsidian navigation intuitive and powerful"
  website: "https://notebooknavigator.com"
  logo: "/images/favicon.svg"
  contact:
    email: "hello@notebooknavigator.com"
    address: "Remote, Global"
  social:
    github: "https://github.com/johansan/notebook-navigator"
    discord: "https://discord.gg/6eeSUvzEJr"
    linkedin: "https://linkedin.com/in/johan-sanneblad"
    twitter: "https://twitter.com/johan_sanneblad"
---

{{< hero 
    title="Modern file explorer for <span class=\"text-gradient\">Obsidian</span>"
    subtitle="Full keyboard navigation. Dual-pane layout. Mobile optimized. Works with 100,000+ notes. Free forever."
    image="hero-preview.png" 
>}}

{{< hero-action text="Install in Obsidian" url="obsidian://show-plugin?id=notebook-navigator" class="btn-primary" icon="download" />}}

{{< hero-action text="View documentation" url="docs.html" class="btn-secondary" />}}

{{< hero-stat value="Free" label="Open source" />}}
{{< hero-obsidian label="Downloads" plugin="notebook-navigator" fallback="51k" />}}
{{< hero-github label="GitHub stars" repo="johansan/notebook-navigator" fallback="431" />}}

{{< /hero >}}

{{% releases 
    label="Latest Updates"
    title="Latest release"
    subtitle="Please post an issue on our GitHub if you have ideas for improvements"
    github="johansan/notebook-navigator"
%}}

Check out the latest releases on [GitHub](https://github.com/johansan/notebook-navigator/releases)

{{% /releases %}}

{{< features 
    label="Features"
    title="Finally, Obsidian feels like home"
    subtitle="The speed of Apple Notes. The beauty of Bear. The productivity of Evernote. The extensibility of Obsidian."
    image="hero-preview.png"
>}}

{{< feature 
    title="Keyboard navigation" 
    icon="keyboard"
>}}
Arrow keys, Tab between panes, Page Up/Down, Home/End. Shift+↑/↓ to extend selection.
{{< /feature >}}

{{< feature 
    title="Dual-pane layout" 
    icon="dual-pane"
>}}
Navigation left, files right. Resizable divider. Auto-reveal active file. Breadcrumb navigation.
{{< /feature >}}

{{< feature 
    title="Pin & organize" 
    icon="star"
>}}
Pin notes to top. Folder notes with clickable links. Custom Lucide icons, emojis, and colors.
{{< /feature >}}

{{< feature 
    title="Hierarchical tags" 
    icon="tag"
>}}
Parent/child tag trees. Drag to tag or Untagged. Favorite tags section. Hide tags by hierarchy.
{{< /feature >}}

{{< feature 
    title="Rich previews" 
    icon="preview"
>}}
1-5 lines preview. Feature images from frontmatter. Date grouping. Clickable tags. Custom per folder.
{{< /feature >}}

{{< feature 
    title="Lightning fast" 
    icon="lightning"
>}}
100,000+ notes. React + TanStack Virtual. IndexedDB + RAM cache. Batch processing engine.
{{< /feature >}}

{{< feature 
    title="Mobile optimized" 
    icon="mobile"
>}}
Touch-friendly buttons. Single-pane mode. Scrollable breadcrumbs. Android, iOS, iPadOS.
{{< /feature >}}

{{< feature 
    title="Quick search" 
    icon="search"
>}}
Instant filtering in current folder. Navigate to folder/tag commands.
{{< /feature >}}

{{< feature 
    title="Multi-selection" 
    icon="copy"
>}}
Cmd/Ctrl+Click toggle. Shift+Click ranges. Cmd/Ctrl+A select all. Batch operations for everything.
{{< /feature >}}

{{< feature 
    title="Frontmatter support" 
    icon="file"
>}}
Custom note names, dates, preview text. Hide notes with properties. Folder note auto-properties.
{{< /feature >}}

{{< feature 
    title="Developer API" 
    icon="code"
>}}
TypeScript API. Metadata control. Navigation & selection. Event subscriptions.
{{< /feature >}}

{{< feature 
    title="Advanced theming" 
    icon="palette"
>}}
80+ CSS variables. Support for Style Settings plugin. Complete theming documentation.
{{< /feature >}}

{{< /features >}}

{{< showcase 
    label="Showcase"
    title="See it in action"
>}}

{{% showcase-item 
    title="Dual-pane interface"
    image="detail-dual-pane.png"
%}}

Navigation tree on the left, file list on the right. Drag to resize. Keyboard Tab to switch panes.

- Folder notes - folders become clickable links with associated notes
- Show notes from descendants - see all subfolder notes at once
- Auto-reveal active file with expand and scroll
- Custom sort order and appearance settings per folder/tag

{{% /showcase-item %}}

{{% showcase-item 
    title="Tag management"
    image="detail-tags.png"
%}}

Hierarchical tags like #project/work/urgent. Drag & drop to add/remove tags instantly.

- Favorite tags - pin frequently used tags to dedicated section
- Drag to "Untagged" to remove all tags from notes
- Hidden tags based on hierarchy (e.g., hiding "archive" hides "archive/2024" etc.)
- Context menu for precise tag operations

{{% /showcase-item %}}

{{% showcase-item 
    title="Rich note previews"
    image="detail-preview.png"
%}}

Configurable 1-5 lines of preview text. Automatic thumbnail generation with Featured Image plugin.

- Feature images from frontmatter or first embedded image
- Date grouping - Today, Yesterday, This Week, Last Week
- Clickable tags with custom colors for visual organization
- Slim mode - compact view without previews when needed

{{% /showcase-item %}}

{{< /showcase >}}

{{< installation 
    label="Installation"
    title="Get started in seconds"
    plugin="Notebook Navigator"
>}}

{{< install-action text="Install in Obsidian" url="obsidian://show-plugin?id=notebook-navigator" class="btn-primary" icon="download" />}}

{{< install-action text="View documentation" url="docs.html" class="btn-secondary" />}}

{{< /installation >}}

{{< about 
    label="About"
    title="Built by an industry veteran"
    name="Johan Sanneblad, PhD"
    subtitle="Passion for coding"
>}}

{{% creator-bio %}}

With a PhD in Software Development and decades of experience building products for companies like Apple, Electronic Arts, Google, Microsoft, LEGO and Volvo Cars, a year ago I decided to see if I could push the boundaries of what users should expect from a modern note-taking application. After six months of planning and six more months of intense development, Notebook Navigator is finally ready for global release.

Most current note-taking apps like Apple Notes, Bear and Evernote seem to be stuck in old legacy frameworks and complex architectures, making it almost impossible for them to innovate with new features. It was time to create a brand new state-of-the-art note-taking experience that was built from the ground up for scalability, performance, and user experience. Something that could be built upon for years, if not decades.

When you use Notebook Navigator I hope you will experience something that has become very rare in the tech industry today: software that is so well-designed throughout that it feels like a natural extension of your brain. This is exactly how Notebook Navigator feels to me, and this is why I built it.

If you have feature suggestions, please post them in our [wiki](https://github.com/johansan/notebook-navigator/wiki). And if you just want to say hi, you're very welcome to join our [Discord server](https://discord.gg/6eeSUvzEJr)!

{{% /creator-bio %}}

{{< creator-links >}}
{{< about-link text="Connect on LinkedIn" url="https://www.linkedin.com/in/johansan/" icon="linkedin" />}}
{{< about-link text="Follow on GitHub" url="https://github.com/johansan" icon="github" />}}
{{< /creator-links >}}

{{< /about >}}

{{< support 
    title="Support the project"
    description="Notebook Navigator is free and open source. If you love using it, consider supporting development."
>}}

{{< support-action text="Sponsor on GitHub" url="https://github.com/sponsors/johansan" class="btn-primary" icon="heart" />}}
{{< support-action text="Buy Me A Coffee" url="https://www.buymeacoffee.com/johansan" image="default-yellow.png" target="_blank" />}}
{{< /support >}}