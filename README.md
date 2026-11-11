# 小怪行囊 · DONLIN KIT

海外数字工具，从这里开始。

网站：<https://donlin-code.github.io/donlinkit/>

这个公开仓库用于发布静态网站，包含首页、六篇早期文章和页面实际引用的资源。详细工具教程仍标注「文档待补充」；早期文章保留其资料整理、教学演示和待验证说明。

## 自动部署

工作流位于 `.github/workflows/deploy-pages.yml`。向 `main` 提交 `site/` 内的更新后，GitHub Actions 会自动发布到 GitHub Pages，也可以在 Actions 页面选择工作流后手动运行。

Pages 的发布来源应为 **GitHub Actions**。部署只使用 `site/`，不需要个人令牌、服务器、域名或额外服务。

## 内容更新

内容源在原来的 `cloud-resident-guide` 项目维护。执行 `node build.cjs` 后，将本次需要公开的网页及相关资源同步到此仓库的 `site/`，再提交更新。修改原项目本身不会自动同步到本发布仓库。

提交前确认内部链接完整；账号、密钥、订单、证件、私人实践记录及未脱敏截图不要上传。

原创文字与 SVG 由小怪行囊整理；引用的官方截图与商标归各自权利方。本仓库未授予第三方商业转载许可。
