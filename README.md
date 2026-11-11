# 绿洲慧写｜开源的专利工作规则

从一个你熟悉的专利任务开始。我们的公开规则说明要读哪些材料、怎样记录依据，以及哪些问题需要专业人员确认。

- [专利撰写 Skills](https://github.com/Tina-patentpro/oasis-patent-skills) · 按业务任务找规则和示例。
- [专利工作流设计源](https://github.com/Tina-patentpro/oasis-dify-workflows) · 研读流程如何组织及所需依赖。
- [团队服务](https://oasisintwrite.com/contact/) · 洽谈 AI 转型咨询、试点和私有化部署。

目前两仓分别提供 15 个独立 Skills 预发布候选与 12 份本地维护的 Dify 工作流设计源；预发布候选与设计源都**不是**已运行验收的成品，具体版本、验证范围与人工复核要求见各仓 README 与随包说明。版本资料请按固定 Release `2026.11.07-rc1` 或固定提交核对。

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
