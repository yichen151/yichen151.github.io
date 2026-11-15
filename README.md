# 郭毅的学术主页

- 英文首页：https://yichen151.github.io/
- 中文页面：https://yichen151.github.io/zh/

## 日常修改

修改 `index.md`（英文）和 `zh/index.md`（中文）。页面顶部的 YAML 字段控制姓名、身份、单位，下面的 Markdown 控制研究方向和联系方式。两种语言分别维护，不自动翻译。

站点地址、主题开关等在 `_config.yml`；少量排版调整在 `assets/css/profile.css`。本项目使用真正的 al-folio 主题组件，模板版本与本地覆盖说明见 `TEMPLATE.md`。未启用博客、新闻、头像、CV、搜索、订阅或外部文章抓取。

## 发布

仓库为公开的 `yichen151/yichen151.github.io`。Settings → Pages → Source 选择 **GitHub Actions**，不要选择分支发布。推送到 `main` 后，Actions 中的 Deploy academic homepage 自动构建并发布。只有成功构建后才替换线上站点；构建失败时先查看失败步骤的日志。

网页上修改文件后点击 Commit changes 即可。电脑修改后：

```powershell
git add .
git commit -m "Update academic homepage"
git push origin main
```

本机无需安装 Ruby 或 Docker，首次构建由 GitHub 完成。

## 以后添加论文

准备真实的论文题目、作者、会议/期刊、年份和链接，再在两种语言页面中增加 Publications / 论文小节。论文多时可恢复 al-folio 的 `_bibliography/papers.bib` 和 publications 布局；主题已保留论文组件依赖。不要展示模板示例论文。

## OpenReview

使用英文首页地址 `https://yichen151.github.io/` 填写个人主页。页面正文包含姓名、单位、身份及公开邮箱；本项目不修改其他 OpenReview 资料。
