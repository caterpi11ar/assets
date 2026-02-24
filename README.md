# caterpi11ar / assets

通用资源库，集中存放品牌标识、图标、版权声明和联系信息等可复用素材。

A centralized store for general-purpose brand and organizational assets — logos, icons, copyright notices, and contact information.

---

## 目录结构 / Folder Structure

```
assets/
├── logo/         # 品牌标志 / Brand logos
├── icon/         # 应用图标 / App & platform icons
├── copyright/    # 版权声明模板 / Copyright notice templates
├── contact/      # 联系信息模板 / Contact info templates
└── skills/       # Agent skill 定义 / Agent skill definitions
```

| 文件夹 / Folder | 用途 / Purpose |
|----------------|---------------|
| `logo/` | 各格式品牌标志（SVG、PNG、深色/浅色变体）/ Brand logos in various formats (SVG, PNG, dark/light variants) |
| `icon/` | 应用图标、favicon、各平台图标集 / App icons, favicons, platform-specific icon sets |
| `copyright/` | 版权声明模板、许可证声明片段 / Copyright statement templates, license notice snippets |
| `contact/` | 联系方式模板（邮箱、社交账号等）/ Contact info templates (email, social handles, etc.) |
| `skills/` | Agent skill 定义（skills.sh），可通过 `npx skills add` 安装 / Agent skill definitions (skills.sh), installable via `npx skills add` |

---

## 使用说明 / Usage

在其他项目中引用本仓库资源时，推荐通过 Git 子模块或直接链接的方式引入。

When referencing assets from this repository in other projects, it is recommended to use Git submodules or direct links.

**Git 子模块 / Git submodule:**

```bash
git submodule add https://github.com/caterpi11ar/assets.git assets
```

**直接引用 / Direct reference:**

将所需文件复制到目标项目中，并在提交信息中注明来源版本。

Copy the required files into the target project and note the source version in the commit message.

**Agent Skill ([skills.sh](https://skills.sh))：**

通过 `npx skills` 安装，让 AI 编程助手自动识别可用资产及其 URL。

Install via `npx skills` so your AI coding agent can automatically discover available assets and their URLs.

```bash
npx skills add caterpi11ar/assets
```

---

## 版权 / Copyright

Copyright © 2026 caterpi11ar. All rights reserved.

本仓库内容仅供 caterpi11ar 内部项目使用，未经授权不得用于商业或外部用途。

The contents of this repository are for internal caterpi11ar projects only and may not be used for commercial or external purposes without authorization.
