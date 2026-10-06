# 校招 AI 产品经理面试辅助 Skill

Cursor Agent Skill。痛点不是题背得少，而是 JD 空泛、不等于真实需求。有学长学姐最准；没有的话，先判断公司在赛道流水线的上游 / 中游 / 下游，再用目标岗 + 同组研发 / 测试 / 运营 / 产品 JD 交叉猜测真实需求，最后给准备清单。

最低输入可以只有公司名（会先查公开招聘）。有人脉口述时，以其为准。本仓库是推断工具，不是内推题库。

## 核心判断

大多数公司吃不完整条流水线，对产品经理的要求因此不同：

- **上游**：做基础产品、技术护城河（基础算法、基础 AI 硬件等）。产品岗少，更要技术思维叠加产品思维，很在意基本功。项目很浅、只是大差不差的应用类 AI，很容易落进八股文套路化面试。
- **中游**：大部分 AI 产品经理的需求口（本 skill 按 TOB 写深）。项目可能用得上，但要体现：如何澄清需求、AI 如何落脚、产品如何设计、出现幻觉如何兜底。考临场、思维、沟通。
- **下游**：甲方，更看重学历。点到为止。

## 安装

文件夹名必须是 `ai-pm-campus-interview`。

- Windows：`%USERPROFILE%\.cursor\skills\ai-pm-campus-interview\`
- macOS / Linux：`~/.cursor/skills/ai-pm-campus-interview/`

```bash
git clone https://github.com/<你的用户名>/ai-pm-campus-interview.git
```

把仓库文件拷进上述目录。需要：`SKILL.md`、`value-chain.md`、`sibling-jd.md`、`public-search.md`、`output-template.md`、`examples.md`。

装好后新开 **Agent** 对话。若 `/` 里看不到，到 Cursor Settings → Rules 看 Agent Decides 是否出现该名称。

## 启动

Agent 输入框打 `/`，选 `ai-pm-campus-interview`，再发材料。也可以 `@` 附上 skill，或说「用校招 AI 产品经理面试 skill 分析 XX 公司」。

## 输入

```text
/ai-pm-campus-interview

公司：
部门/业务线（若知道）：

【目标岗 JD】校招产品 / AI 产品经理全文

【同组或同批 JD】信息面越多越好
- 算法/研发：
- 测试：
- 实施/售前（若有）：
- 运营（若有）：
- 其他产品岗：

【简历】可选
【学长学姐原话】可选，优先级最高
```

没贴 JD 时会先查公开招聘，再出完整拆盘。

## 输出

生态位与置信度；这组大概要干什么、各类岗位需求浓度；面试主形态；建议准备的内容（P0/P1、口述轴、追问、7 天安排）；公开岗位清单。
