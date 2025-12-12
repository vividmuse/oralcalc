# oralcalc
oral calculation generator

小学口算题生成程序

[点击此处查看示例](https://hldgaofeng.github.io/oralcalc/)

![](https://hldgaofeng.github.io/oralcalc/shot1.jpg)

## 更新要点
- 支持快捷题型：20 以内/100 以内无进借、进位加法（1/2 位）、借位减法（1/2 位）、连加连减等常用组合，一键套用范围与规则。
- 数字格式增强：可选整十数、小数（1/2 位）、真分数/假分数/带分数；自动生成试卷标题并可手动覆盖。
- 组合题型与去重：可将多套配置拼成批量题目，支持同页不重复。

## 本地开发
直接打开 `index.html` 即可在浏览器预览，无需构建步骤。

## 部署
### GitHub Pages
1. 将代码推送到 GitHub 仓库，例如 `main` 分支。
2. 在仓库 Settings → Pages 选择源分支（`main`）和根目录 `/`，保存。
3. 等待构建完成后，通过 Pages 提供的域名访问。

### Cloudflare Pages
1. 在 Cloudflare Pages 新建项目并连接 Git 仓库。
2. 构建设置：Framework 选择 “None”，Build command 留空，Build output directory 设置为 `/`。
3. 触发部署，完成后使用 Cloudflare 提供的域名或自定义域访问。
