# 绿洲慧写 · OasisIntWrite

把中国专利撰写的专业方法写成可下载、可审阅、可核对边界的公开成果：
**面向具体环节的独立 Agent Skills**，以及**专利业务 Dify 工作流的本地设计源**。
面向专利代理师、企业 IP 团队与 Agent／Dify 开发者；辅助的是材料整理、方法复用与编排研读，
不是已验收的成品服务。

## 先看哪一个：两个代表问题

| 你想弄明白的问题 | 从哪份材料开始 |
|---|---|
| 研发材料不完整、缺实验和附图时，怎样整理交底并保留待确认项？ | [oasis-patent-skills](https://github.com/Tina-patentpro/oasis-patent-skills) 的 `M05 patent-technical-disclosure`：读独立合同与调用请求示例，看「已知关系整理＋未读／未知／待确认显式保留」的写法 |
| 一个技术背景研究环节，怎样编成可阅读、可比较的 DSL 图？ | [oasis-dify-workflows](https://github.com/Tina-patentpro/oasis-dify-workflows) 的 `Flow-1-1`（V1.0.2）：只读看 `workflow.graph.nodes`／`edges`、提示词与变量 |

两份材料都从固定版本 `2026.11.07-rc1` 开始看。最短阅读路线：
到对应仓 Release 页取该 tag → 用 `catalog.json` 核对文件名与版本 → 读包内 `SKILL.md`／
`examples/usage.md` 或该流程的 `NOTES.md` → 先做无模型、无导入的静态审阅。
若用 `git clone`，请 checkout 同一 `2026.11.07-rc1` tag／固定 commit；`main` 不自动等于 rc1。
集合版本不等于单个包或单份 YML 的版本，逐项以各仓 `catalog.json` 为准。

## 给三类读者

- **专利代理师／专利工程师**：看 M05 的输入输出合同，以及「缺材料时仍整理已有内容，并明确标注缺口与待确认项」的处理方式，判断这套方法是否适合你的材料整理流程；输出一律需人工专业复核。
- **企业 IP／研发负责人、专利所管理者**：先看两仓的「不面向」「费用」「数据外发」与来源许可说明，再判断是否需要就部署与材料边界进一步交流；公开仓不含模型凭据、知识库或后台服务。
- **Agent／Dify 开发者**：按固定 ref 取文件，在自有隔离环境复现与适配；两仓 `CONTRIBUTING.md` 写明版本规则与不得提交的材料。

## 试读 / 反馈

从两仓 `2026.11.07-rc1` Release 下载，按仓内 `docs/installation.md` 或 `docs/import-guide.md`
的最短路线开始。遇到问题请到对应仓 GitHub Issues，附资产 ID、集合 ref／包版本、manifest 或
YML SHA-256、Host 或 Dify 版本、最小非敏感输入与步骤、预期与实际、已做检查和脱敏证据。
不要在公开 Issue 提交真实案件、客户材料或任何密钥。

## 团队咨询 / 私有部署交流

团队收费服务、系统演示、培训陪跑、私有化部署与定制工作流属与上述公开成果分离的商业事项，
范围与价格另行确认；这里不设固定价格、不承诺服务等级或效果指标。
请通过[官网联系页](https://oasisintwrite.com/contact/)说明**非敏感**的组织类型、
所需业务环节与部署约束；可先提出本地／内网部署、模型选择、数据外发、权限隔离、日志与删除等要求，
由双方进一步评估范围与验收证据。详细技术材料待双方确认渠道后再提供，不要在公开仓库提交。

## 请先读这一段边界

公开成果是**实验性候选与历史设计源**：逐文件身份校验、静态解析与机械检查已有记录。
上游有限记录保留两次图像调用及有限模式观察，尚未取得全 15 包的真实运行验收；
对本公开集合的准确版本，新环境安装／导入验证、专业具名审阅与用户接受未取得，
有限观察不证明所有包、Host 或工具模式通过。工作流仓的 YML 是本地维护的设计源，
**不是 Dify 实例上已发布应用的导出**。输出一律需人工专业复核，不可直接递交；
这里不提供可授权、FTO、授权率或节时效果承诺。模型推理、检索与图像服务由使用方自己的
Host／服务商提供，通常按量计费；把未公开技术材料交给第三方模型前，请自行确认保密要求。
仓库公开或服务器本地部署本身不能证明模型请求不外发。详见各仓 `docs/verification-and-limits.md`。

## 其他公开仓库

产品工程快照：`DSH-Oasis`、`oasis-dsh-professional-workbench`、`oasis-frontend`；
专业工具与方法：`patent-skill-distillery`、`oasisintwrite_image_editor`；
其他独立成果：`dsh-opentcs`、`ThinkBookFanControl-Smart`、`maidou-grade1-family-learning`、
`desktop-tutorial`。它们各有自己的受众与许可状态，不都属于专利能力产品线。

许可：两主仓按各自 LICENSE／NOTICE 声明采用 Apache-2.0，权利主体 OasisIntWrite；
第三方组件和其他仓库按各自许可及公开范围核对。
