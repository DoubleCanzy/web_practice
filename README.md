# Web Projects

`G:\web-projects` 下 Web 学习与练习项目的总览。

## 目录结构

```
web-projects/
├── practice/            # HTML & CSS 学习练习（对应 GitHub 仓库 web_practice）
│   ├── HTML&CSS/        # 基础练习项目（roadmaps.sh）
│   └── MDN_test/        # MDN 教程练习文件
├── project/
│   └── plli_library/    # PLAVE Library：React 粉丝资料站
└── 素材/                 # 设计素材（PSD 背景图等）
```

## practice — HTML & CSS 学习项目

HTML 和 CSS 的学习与练习项目集合。

### 目录结构

```
practice/
├── HTML&CSS/
│   ├── Basic/                 # 基础练习
│   │   ├── single-page-cv/        # 单页简历（CV）
│   │   ├── Basic HTML Website/    # 多页纯 HTML 网站（导航/SEO/表单）
│   │   ├── portfolio-website/     # 响应式作品集网站（Flexbox/媒体查询/深色模式）
│   │   ├── Changelog Component/   # 更新日志组件（时间轴/定位/响应式）
│   │   ├── testimonial-cards/     # 评价卡片墙：PLAVE 成员（气泡/星级/头像堆叠）
│   │   ├── Datepicker UI/         # 日期选择器 UI（纯 CSS：定位/日期网格）
│   │   ├── accessible-form-ui/    # 无障碍表单（ARIA/焦点态/对比度）
│   │   ├── image-grid/            # 照片网格（CSS Grid 跨行跨列/响应式）
│   │   ├── tooltip-ui/            # 导航气泡提示（定位/hover/五种动画）
│   │   ├── pricing-comparison-table/ # 订阅方案对比表（语义化表格/无障碍）
│   │   ├── blog-post-page/        # 博客文章页（长文语义标记/纯 HTML）
│   │   ├── contact-form/          # 联系表单（表单接线/校验/fieldset）
│   │   ├── photo-showcase/        # 照片展（图片 alt/宽高/图注/视频）
│   │   ├── pricing-cards/         # 定价卡片（Flexbox 等高/hover/focus）
│   │   └── WORKFLOW.md            # 工作流笔记
│   └── practice/               # 进阶练习
│       └── 1.视差滚动/          # 视差滚动效果练习
└── MDN_test/                   # MDN 教程练习（HTML/CSS/少量 JS）
```

### 项目列表

| 项目 | 说明 | 参考网站 |
| --- | --- | --- |
| [single-page-cv](practice/HTML&CSS/Basic/single-page-cv/) | 单页简历，HTML + CSS 练习 | [Single-Page CV](https://roadmap.sh/projects/single-page-cv) |
| [Basic HTML Website](practice/HTML&CSS/Basic/Basic%20HTML%20Website/) | 多页纯 HTML 网站：语义化结构、SEO、表单 | [Basic HTML Website](https://roadmap.sh/projects/basic-html-website) |
| [portfolio-website](practice/HTML&CSS/Basic/portfolio-website/) | 响应式作品集网站：Flexbox、媒体查询、深色模式 | [Portfolio Website](https://roadmap.sh/projects/portfolio-website) |
| [Changelog Component](practice/HTML&CSS/Basic/Changelog%20Component/) | 更新日志组件：时间轴、CSS 定位、响应式 | [Changelog Component](https://roadmap.sh/projects/changelog-component) |
| [testimonial-cards](practice/HTML&CSS/Basic/testimonial-cards/) | 评价卡片墙：PLAVE 成员（气泡、星级、头像堆叠） | [Testimonial Cards](https://roadmap.sh/projects/testimonial-cards) |
| [Datepicker UI](practice/HTML&CSS/Basic/Datepicker%20UI/) | 日期选择器 UI：纯 CSS 定位与日期网格 | [Datepicker UI](https://roadmap.sh/projects/datepicker-ui) |
| [accessible-form-ui](practice/HTML&CSS/Basic/accessible-form-ui/) | 无障碍表单：ARIA、焦点态、WCAG 对比度 | [Accessible Form UI](https://roadmap.sh/projects/accessible-form-ui) |
| [image-grid](practice/HTML&CSS/Basic/image-grid/) | 照片网格：CSS Grid 跨行跨列、响应式断点 | [Image Grid](https://roadmap.sh/projects/image-grid) |
| [tooltip-ui](practice/HTML&CSS/Basic/tooltip-ui/) | 导航气泡提示：定位、hover、五种入场动画 | [Tooltip UI](https://roadmap.sh/projects/tooltip-ui) |
| [pricing-comparison-table](practice/HTML&CSS/Basic/pricing-comparison-table/) | 订阅方案对比表：语义化 table、scope、colspan | [Pricing Comparison Table](https://roadmap.sh/projects/pricing-comparison-table) |
| [blog-post-page](practice/HTML&CSS/Basic/blog-post-page/) | 博客文章页：长文语义标记（blockquote/code/figure） | [Blog Post Page](https://roadmap.sh/projects/blog-post-page) |
| [contact-form](practice/HTML&CSS/Basic/contact-form/) | 联系表单：name/value 接线、校验、fieldset/legend | [Contact Form](https://roadmap.sh/projects/contact-form) |
| [photo-showcase](practice/HTML&CSS/Basic/photo-showcase/) | 照片展：图片 alt/宽高、figure 图注、内嵌视频 | [Photo Showcase](https://roadmap.sh/projects/photo-showcase) |
| [pricing-cards](practice/HTML&CSS/Basic/pricing-cards/) | 定价卡片：Flexbox 等高、推荐位突出、按钮状态 | [Pricing Cards](https://roadmap.sh/projects/pricing-cards) |
| [视差滚动](practice/HTML&CSS/practice/1.视差滚动/) | Parallax scrolling 视差滚动效果 | —— |

## project — plli_library（PLAVE Library）

PLAVE 粉丝资料站，同时是一个 React 自学项目。阶段一为纯静态内容站，数据来自本地 JSON。

### 技术栈

- React 19 + Vite
- React Router 8（多页路由）
- ESLint（代码规范）

### 页面

首页（Home）、地点（Locations）、成员列表/详情（Member List/Detail）、资讯列表/详情（News List/Detail）、时间线（Timeline）、视频（Video）、404

### 数据

本地 JSON（`src/data/`）：`members`、`news`、`plave-restaurants`、`timeline`

### 项目文档

- `docs/`：需求（requirements）、技术规范（tech-spec）、设计规范（design-spec）、路线图（roadmap）、内容清单（content-plan）
- `devlog/`：总进度看板（PROGRESS.md）+ 每日开发日志

### 常用命令

```bash
npm install     # 安装依赖
npm run dev     # 开发服务器
npm run build   # 构建
npm run lint    # 代码检查
npm run preview # 预览构建产物
```

## 素材

设计素材：PSD 背景图等（仅供本地使用，不参与任何代码项目）。
