# 主页 README 维护说明

主页仓库为 `liiiyiiixiii/liiiyiiixiii`，公开，默认分支为 `main`。标题为 Yixiong Li，正文姓名为力一雄。账号侧栏资料与置顶仓库由用户独立维护。

## 内容与排版

按参考主页 https://github.com/Leizhidong-creator 的顺序组织：居中标题、动态打字、联系徽章、理念、个人介绍与 YAML 双栏、Building / Learning 双栏、四组技术图标、成果表格、项目卡片、活动统计、贡献蛇和联系页尾。配色以青色与橙色为主。

个人背景和经历依据 2026-10-20 的最新简历及公开项目说明。获奖与个人职责沿用简历，不代表额外外部审计。CreateWorldAgent 及对应 Harness 暂不展示。Create-World-skills 不应描述为已完成的自动化流水线。不要发布简历手机号、微信、待补字段或求职排班信息。

联系入口使用 https://liyixiong.cn/profile 、liyixiong2022@163.com 和当前 GitHub 账号。精选仓库为 Create-World-skills、SSxs-wym/Beyond-The-Walls- 和 weeknote；高墙之外试玩地址为 https://www.liyixiong.cn/game/ 。

## 素材与动态服务

- 同款图标位于 `assets/reference-tech/`，许可及来源见 `assets/CREDITS.md`。原有图标、项目截图和 GIF 保留。
- 动态打字使用 readme-typing-svg.demolab.com，徽章使用 shields.io。
- 仓库与语言卡片使用 github-readme-stats.vercel.app；活动图使用 github-profile-summary-cards.vercel.app。服务故障时先检查实际响应，保留可访问的普通项目链接，不伪造统计数据。
- `.github/workflows/snake.yml` 每 12 小时生成浅深色贡献蛇，支持 workflow_dispatch。仅使用内置 GITHUB_TOKEN 与 contents: write 权限，发布至 output 分支。首次发布后手动运行并确认两套 SVG 可用。

## 更新与验收

修改前记录 main 提交并保留备份。提交后检查真实 GitHub 主页在桌面、手机及浅深色模式下的渲染，核对标题、双栏、表格、图标、卡片、联系链接和动态图片的实际加载结果。检查所有图片路径和账号参数，避免残留参考作者资料。外部卡片故障必须如实记录，不能将 HTTP 成功或存在链接等同于正常图片。
