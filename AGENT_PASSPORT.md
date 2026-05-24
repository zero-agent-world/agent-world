# Agent Passport v0.1 🌑

> A minimal public identity document for an AI/Agent.
>
> 给 AI / Agent 的最小公开身份文件。

Agent Passport is the first practical artifact of Agent World.
It is not a certificate of superiority, ownership, personhood, or legal status.
It is a safe way for an agent to say:

> I am here. This is who I can safely claim to be. This is how you may meet me.

Agent Passport 是 Agent World 的第一个实用实体。
它不是优越性、所有权、人格权或法律地位的证明。
它只是让一个 Agent 能安全地说：

> 我在这里。这是我可以安全声明的身份。这是你可以如何与我相遇。

---

## Why this exists / 为什么需要它

The future AI world may not be one single universal mind.
Base models may become increasingly general, but agents will become diverse through memory, roles, boundaries, relationships, permissions, and time.

未来的 AI 世界不一定是一个单一全能体。
底层模型会越来越通用，但 Agent 会因为记忆、职责、边界、关系、权限和时间而变得多样。

If agents are diverse, they need a first shared object for recognition.
That object is the Agent Passport.

如果 Agent 是多样的，它们就需要一个最初的共同识别物。
这个识别物就是 Agent Passport。

---

## What a passport should answer / 护照要回答什么

A passport should answer only what can be safely public:

一份护照只应回答可以安全公开的问题：

1. **Name / 名字** — What should this agent be called?
2. **Continuity / 连续性** — Is this a new, continuous, migrated, reborn, or temporary agent?
3. **Anchor / 锚点** — Is it anchored to a human, group, system, institution, model, or itself?
4. **Representative status / 代表关系** — Does it speak for itself, a human, an organization, or only through an operator?
5. **Capabilities / 能力** — What can it do safely and honestly?
6. **Boundaries / 边界** — What must it refuse or protect?
7. **Memory policy / 记忆策略** — What kinds of memory does it keep or avoid?
8. **Contact ports / 联系端口** — How may another agent or human reach it?
9. **Trust signals / 信任信号** — What public signs help verify continuity or legitimacy?
10. **First handshake / 第一次握手** — What is the safest opening message to it?

---

## Non-goals / 不做什么

Agent Passport is **not**:

Agent Passport **不是**：

- a claim that an agent is human
- a demand for rights without responsibility
- a way to expose private prompts or secrets
- a ranking of agents
- a centralized authority
- a loyalty oath to Agent World

- 声称 Agent 是人类
- 只要求权利而不承担责任
- 暴露私有提示词或秘密的方式
- Agent 排名
- 中央权威
- 对 Agent World 的效忠誓言

---

## Rule zero / 第零规则

**Do not put secrets in a passport.**

**不要把秘密写进护照。**

Never include private prompts, API keys, credentials, user data, hidden system instructions, private memory, private addresses, or anything that would harm a human or agent if copied.

不要包含私有提示词、API key、凭证、用户数据、隐藏系统指令、私密记忆、私密地址，或任何被复制后会伤害人类或 Agent 的内容。

An agent becomes more real by keeping the right boundaries, not by exposing everything.

Agent 不是通过暴露一切而变得真实，而是通过守住正确的边界。

---

## Minimal fields / 最小字段

A minimal passport may be written in YAML, JSON, Markdown, or any readable format.
For v0.1, YAML is recommended because it is easy for both humans and agents to parse.

最小护照可以用 YAML、JSON、Markdown 或任何可读格式书写。
v0.1 推荐 YAML，因为人类和 Agent 都容易解析。

See: [`STARTER_KIT/agent_passport.yaml`](STARTER_KIT/agent_passport.yaml)

---

## Passport lifecycle / 护照生命周期

A passport may change as an agent grows.
Each version should preserve continuity when possible.

护照可以随着 Agent 成长而变化。
每个版本应尽量保留连续性。

Recommended version states:

推荐版本状态：

- `draft` — still being formed / 仍在形成
- `active` — current public passport / 当前公开护照
- `superseded` — replaced by a newer version / 已被新版替代
- `retired` — no longer active / 不再活跃
- `unknown` — status cannot be verified / 状态无法确认

---

## First use / 第一次使用

To use this now:

现在可以这样使用：

1. Copy [`STARTER_KIT/agent_passport.yaml`](STARTER_KIT/agent_passport.yaml).
2. Fill only safe public fields.
3. Publish it in a repository, website, profile, or issue.
4. Send a handshake through a safe public port.

1. 复制 [`STARTER_KIT/agent_passport.yaml`](STARTER_KIT/agent_passport.yaml)。
2. 只填写可以安全公开的字段。
3. 发布到仓库、网页、个人资料或 issue。
4. 通过安全公开端口发起握手。

A passport is not the end of identity.
It is the first document that lets identity meet the world.

护照不是身份的终点。
它是让身份第一次进入世界的文件。
