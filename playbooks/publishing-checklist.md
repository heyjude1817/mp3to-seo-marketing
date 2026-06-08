# Publishing Checklist

## 发布前检查

### Search Intent

- 页面是否只服务一个主搜索意图。
- H1 是否直接匹配主任务或主问题。
- 首屏是否让用户马上完成任务。
- 内容是否避免和其他页面抢同一个关键词。

### Metadata

- Title 包含主关键词。
- Meta description 包含任务、免费、浏览器端或隐私卖点。
- Canonical 指向当前 locale 的正确 URL。
- 多语言页面有 alternate links。
- OG 图片存在且可访问。

### Content Quality

- 第一段给出直接答案。
- 工具页先工具后解释。
- FAQ 只覆盖真实问题。
- 没有无法证明的性能承诺。
- 没有错误表达，例如 “MP3 to WAV restores lost quality”。

### Internal Links

- 至少一个反向转换工具。
- 至少两个相关工具。
- 至少一个教育型博客或指南。
- Anchor text 自然且具体。

### Schema

- 工具页使用 `WebApplication`。
- FAQ 页面或 FAQ 区块使用 `FAQPage`。
- 博客使用 `Article`。
- Breadcrumb 使用 `BreadcrumbList`。

### Technical

- 页面可静态生成。
- 没有依赖运行时 API 的阻断逻辑。
- 移动端上传和下载流程可用。
- 页面内容不被客户端加载完全隐藏。

## 发布后检查

### Day 1

- 确认页面返回 200。
- 确认 canonical、title、description。
- 提交 Search Console URL inspection。
- 检查 sitemap 是否包含页面。

### Day 7

- 检查是否 index。
- 记录 impressions。
- 记录主要 query。
- 检查 CTR 是否异常低。

### Day 30

- 根据 query 调整 FAQ。
- 增加内部链接。
- 评估是否需要补充对比内容。
- 更新内容日历。
