# 按任务引入技能

只读取当前阶段需要的技能，并在首次使用时简短说明它帮助解决什么。以本轮可用技能目录为准，不将下列列表当成已安装清单。读取目标 SKILL.md 后遵守其前置要求；本文件不替代专门技能。

用户目标和明确选择优先。避免多个技能同时改写同一设计方向；项目已确定的产品目标、设计规则和范围作为共同依据。若其他技能要求用户选择或额外素材，而现有授权与资料已满足要求，不重复提问；真正缺少必需信息时解释来源并等待。

| 任务 | 引入的技能 | 使用时机与边界 |
| --- | --- | --- |
| 新 UI、明显 UI 改造 | `frontend-design` | UI 阶段必须读取并调用；持续实现遵循已确定规则。现有组件的小修复保留既有风格。 |
| 用户希望完整网站／网站发布 | `sites:sites-building`、`sites:sites-hosting` | 按技能适用范围使用；既有普通 Web 仓库不因本工作流而迁移到 Sites，明确指定其他托管方式时尊重用户选择。发布遵循当时授权。 |
| 视觉方向探索、图像方案、忠实实现参考 | `product-design:index` 及对应 focused skill | 用户要求这类设计任务或图片／URL 复刻时读取；按其路由执行。完整普通开发任务不会仅因包含 UI 而自动启动 Product Design。 |
| 评审现有产品体验 | `product-design:audit` | 对实际界面或流程做 UX、设计、可访问性评审时使用；先截图再报告。不要只用代码检查冒充界面评审。 |
| 产品确实需要位图素材 | `imagegen` | 产品照片、插画等提升结果时使用；原生 CSS、SVG、现有图标更合适时沿用。调用前读取技能。 |
| Figma 到代码、写入 Figma | 对应 `figma:*` 技能 | 用户给 Figma 设计或要求 Figma 工作时使用，遵守相关工具的强制前置技能。 |
| 含真实数据分析、图表、KPI 的产品任务 | `data-analytics:index` 及 focused skill | 数据定义、来源、计算或分析结论影响结果时使用；普通设置页和 CRUD 不仅因出现数字就进入数据分析工作流。 |
| 文档、PDF、电子表格、幻灯片是交付物 | 对应 documents、pdf、spreadsheets、presentations 技能 | 用户实际需要这些格式或处理文件时使用；不强制把产品规格导出为这些格式。 |
| 解释复杂选择或机制需要交互视觉 | `visualize:visualize` | 可视化能帮助用户作决定时使用；简单问答或短规格直接写清楚。 |
| Codex／OpenAI 的设置、模型与产品用法 | `openai-docs` | 回答对应产品问题时按它的查证方式执行，不因 agent 在 Codex 中运行而加载。 |

## 可选补强

[Impeccable](https://github.com/pbakaus/impeccable) 的 critique、distill、harden、polish 分工，[interface-design](https://github.com/Dammyjay93/interface-design) 的设计记忆，以及 [Emil Kowalski](https://github.com/emilkowalski/skills) 的设计工程规则，都是本工作流的参考做法。它们没有出现在当前技能目录时，不声称已调用，也不擅自安装。可以用本流程的验收标准完成工作；用户明确要求安装时使用 `skill-installer`。

`frontend-design` 是本流程唯一明确要求的 UI 技能。缺失时寻找可能的已安装路径；确实不可用则说明 UI 阶段缺少该依赖，继续不依赖它的规划。涉及新增安装时按用户现有授权处理，不能假装调用成功。
