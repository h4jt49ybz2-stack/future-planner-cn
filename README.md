# 向前 · 生涯路径规划

一款面向不同教育背景、工作经历与职业阶段的中文生涯规划网页。无正式学历、在校、正在工作、转行、重返职场、自由职业或仍在探索的人都可以使用。

## 功能

- 可选记录教育与培训、工作年限、工作 / 项目 / 照护 / 社区经历、技能和资格
- 比较就业、继续学习或培训、转型、重返职场及稳定工作等路径
- 按职业方向、地区和个人现实约束整理招聘条件
- 将个人资料与真实招聘页面中的筛选项逐条对照，给出“符合 / 待核实 / 存在差距”的辅助判断
- 每条样例都链接到公司或招聘机构原文，并显示原文核对日期
- 导入 CSV、手动维护岗位、人工复核条件，支持打印和导出 PDF

## 真实招聘标准样例

网页内置了几条不同经历阶段和学历门槛的公开职位样例：

- [Amazon：有经验软件开发工程师](https://www.amazon.jobs/en/jobs/10572015/software-development-engineer-amazon)——专业工作年限、架构经验、编程语言；相关学位是优先条件
- [百度：2027 AIDU 大模型 Infra 工程师](https://talent.baidu.com/jobs/detail/GRADUATE/3fbd2b8c-43a6-4fa6-a71c-784bfe2ec4cd)——学历、届别、专业和技术技能要求
- [Amazon UK：Software Development Engineer – 2026](https://www.amazon.jobs/en/jobs/10408763/software-development-engineer-2026)——毕业日期、相关学位和计算机基础要求；历史届别样例
- [Barchester Healthcare：NHS Jobs Receptionist 历史职位](https://beta.jobs.nhs.uk/candidate/jobadvert/E0177-26-3307)——公告明确不要求正式学历，同时列出沟通能力和 DBS 审查；职位已关闭，仅用于说明筛选条件可以不同

以上页面于 2026-10-27 核对。职位是否开放、要求是否变化，请点击原文重新确认。系统只做有限的文字和数字比较；不能判定资格等同性、真实熟练度、工作许可或录用概率。“待核实”不是“不符合”。

## 本地运行

页面没有构建步骤和第三方依赖。用浏览器打开 `dist/index.html` 即可；也可以将 `dist/` 部署到静态网站托管服务。

## 数据与隐私

个人资料、岗位清单和任务保存在当前浏览器的 `localStorage` 中。导入的 CSV 在浏览器本地读取，不会上传。请勿在共享设备上填写不希望他人看到的信息；清除浏览器网站数据会删除本地保存内容。

## 许可证

本项目采用 GNU General Public License v3.0（GPL-3.0-only），详见 [LICENSE](LICENSE)。
