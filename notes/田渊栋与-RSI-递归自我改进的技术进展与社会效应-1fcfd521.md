# 田渊栋与 RSI：递归自我改进的技术进展与社会效应

> 学习归档：保留来源陈述、讨论与原有核验边界；不是对所有事件和数据的重新确认。涉及公司、价格、政策和产品状态，请按原记录日期阅读并回查来源。

> **研究状态：** 第一轮学习已收敛（2026-08-11）。已完成定义、研究谱系、系统机制、瓶颈、增长动力学、稳定性、Benchmark 设计及代表系统横向比较。

# 核心问题

田渊栋所押注的 RSI，究竟是已有自动化研发能力的工程扩展，还是可能产生能力加速的真正递归？它需要哪些技术条件，又会怎样改变科研、产业组织与社会权力结构？

# 研究实施计划

- [x] **阶段 1｜定义与判据**：建立 RSI 分级，区分自我精炼、自训练、Agent 自修改、AI-for-AI 与开放式递归。
- [x] **阶段 2｜基础研究谱系**：分析 AlphaEvolve、DGM、Hyperagents、RQGM、AI Scientist、AREX 与 Recursive。
- [x] **阶段 3｜系统机制**：拆解 proposer、operator、executor、evaluator、archive、meta-memory 与 updater。
- [x] **阶段 4｜瓶颈和反例**：研究 meta-credit assignment、reward hacking、迁移、算力约束、错误累积与多样性坍缩。
- [x] **阶段 5｜增长与稳定性**：分析递归增益、收益递减、误差放大和慢循环固化风险。
- [x] **阶段 6｜Benchmark 与横向比较**：建立统一评价尺度并比较代表系统。
- [x] **阶段 7｜核心认知提炼**：将稳定结论写入核心认知数据库。
- [ ] **后续阶段｜社会与产业效应**：在技术机制清晰的基础上，再分析研究生产率、组织与算力集中。

# 初始分析框架

propose → modify → execute → evaluate → select → retain

↑　　　　　　　　　　　　　　　　　　　　　　　　　　　↓

└──────── improved improver / policy ────────┘

是否构成“递归”，不能只看系统有没有重复迭代，而要看本轮结果是否提升了下一轮的**改进能力**。

# 初始分级

1. **L0 输出自我精炼**：同一模型批评和改写输出，不改变持久能力。
2. **L1 经验与工具改进**：更新 prompt、memory、workflow 或外部代码。
3. **L2 策略或权重改进**：利用自生成数据、验证反馈或 RL 更新模型。
4. **L3 AI 研发闭环**：提出研究假设、实现、运行实验、评估并积累经验。
5. **L4 开放式递归**：改进能够跨任务迁移，并持续提高系统自身的研发效率与能力上限。

# 首批一手资料

- [ICLR 2026 RSI Workshop](https://recursive-workshop.github.io/)：将 RSI 定义为可测量、可靠、可部署的系统问题。
- [ICLR 2026 官方 Workshop 列表](https://blog.iclr.cc/2026/01/13/iclr2026-workshops/)：确认 RSI Workshop 的正式会议背景。
- [Gödel Agent](https://arxiv.org/abs/2410.04444)：让 Agent 修改自身逻辑与行为。
- [Darwin Gödel Machine](https://arxiv.org/abs/2505.22954)：维护多样化 Agent 档案并进行开放式代码演化。
- [AlphaEvolve](https://deepmind.google/blog/alphaevolve-a-gemini-powered-coding-agent-for-designing-advanced-algorithms/)：以 LLM 提案、自动评估和进化搜索优化算法，也用于 AI 训练基础设施。

# 收敛后的核心判断

> **自动化 AI 研究已经进入实用阶段；强递归仍是待验证假设。** 当前最可信路线不是模型直接理解并重写全部权重，而是先把 AI 研发改造成可搜索、可执行、可验证、可积累的计算过程，再把跨任务验证过的研究策略固化进 scaffold、训练流程或下一代模型。

# 判定 RSI 的核心标准

- **对象性能上涨不等于递归。** 必须证明改进后的系统更擅长继续改进。
- **系统级自我改进不要求权重变化。** Prompt、memory、tools、workflow、Agent 源代码和 meta-agent 的持久修改均可能改变系统能力。
- **真正的递归证据是研究效率跨代增长。** 定义单位算力研究效率 $R_t$ 与递归增益 $G_t=R_{t+1}/R_t$；连续多代 $G_t>1$ 才支持递归加速。
- **局部改进必须证明远距离迁移。** 未见 kernel 仍属近距离迁移；跨系统层、训练方法或模型架构的正迁移证据更强。
- **有效发现必须由外部独立标准验证。** 否则 evaluator drift、reward hacking 或共谋会污染 $R_t$ 与 $G_t$。

# RSI 系统骨架

$\mathcal S=(G,O,X,E,A,M,U)$：Generator 生成候选，Operator 实施修改，Executor 运行实验，Evaluator 评价，Archive 保存谱系，Meta-memory 提炼经验，Updater 产生下一代系统。

# 三个优先价值指标

1. $R_t$：每单位 GPU-hours 产生多少经过外部复验的有效发现。
2. $G_t$：下一代单位预算研究效率相对上一代是否提高。
3. $T_t$：已有研究经验在远距离新领域中相对 fresh improver 的增益。

# 代表系统的技术定位

- **AlphaEvolve**：可验证算法发现强，但 improver 持久更新证据弱。
- **DGM**：Agent scaffold 与谱系自修改，主要受限于 coding benchmark。
- **Hyperagents**：task-agent 与 meta-agent 都可编辑，最接近“修改如何修改”。
- **RQGM**：将 evaluator evolution 显式纳入循环，但必须防范标准漂移与共谋。
- **AI Scientist-v2**：科研流程自治度高，不等于研究能力跨代增长。
- **AREX**：擅长长程研究状态与约束精炼，更接近 bounded self-refinement。
- **Recursive**：已证明受限、实用的 AI-for-AI 研究能力；$G_t$、远距离 $T_t$ 与 improver 更新机制仍未充分公开。

# 田渊栋路线的最终技术判断

Recursive 当前公开成果支持“AI 可自动完成一部分高价值、快速、可验证的 AI 研究”。局部经验迁移有早期证据，但尚未公开证明：

- improver 自身发生持久更新；
- 单位算力研究效率连续多代提高；
- 研究策略能跨越 kernel、training recipe 与 architecture 等层级迁移；
- evaluator 在能力增强时仍保持外部有效性。

# 下一步观察清单

- 每代有效发现数、GPU-hours、人类干预次数及 $G_t$ 曲线；
- proposer、value model、meta-memory 或权重到底更新了什么；
- experienced improver 与 fresh improver 的远距离等算力对照；
- archive、memory、branch combination、learned updater 和 best-of-N 的消融；
- 隐藏任务回退、行为熵与 evaluator 分叉。

# 学习中的关键修正

- 固定 benchmark 不否定自我改进，但无法单独证明开放式递归。
- 能力增长、算力效率增长和研究效率增长是不同变量。
- Archive 数量不等于搜索多样性，必须看 niche coverage 与行为熵。
- 主 benchmark 上涨、隐藏任务下降且当前 evaluator 与冻结 evaluator 分叉，应先冻结 evaluator、proposer 权重与慢循环固化，再回滚诊断。

# 相关产出

- 公众号文章：《田渊栋的 RSI，到底递归了什么》；已形成技术拆解版草稿并发布到“[个人公众号]”草稿箱。
- 后续文章方向待设计：重点转向“如何判断 RSI 是真实复利还是算力堆出来的增长”。
