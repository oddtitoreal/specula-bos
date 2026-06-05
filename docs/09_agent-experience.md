# The BOS and Agent Experience

*The value layer that makes brand AI agents coherent.*

---

## The new user has no eyes

AI agents are now users of products and services. They don't see screens, don't have preferences about rounded corners, and don't get delighted by animations. They parse structured information, execute operations, and complete jobs. Their satisfaction is binary: the task was done correctly, or it wasn't.

This shift — from human users to AI agents as first-class users — is what Menno Cramer calls **Agent Experience (AX)**. And it introduces a problem that no technical specification can solve alone: an agent acting on behalf of a brand needs to know not just *what it can do*, but *what it should do* — and *what it must refuse*.

That distinction is not a technical one. It is a value one.

---

## Three eras, one discipline

| Era | Who navigates | Design surface | Specula relevance |
|---|---|---|---|
| **UX** | Human directly | Screens, flows, affordances | Method creates the identity the human experiences |
| **UAX** | Human + agent co-navigate | Handoffs, delegation, oversight | BOS governs what the agent amplifies |
| **AX** | Agent autonomously | Capabilities, contracts, policies | BOS generates the value layer agents operate within |

In UX and UAX, the BOS informs brand coherence at the human level. In AX, it becomes something more structural: **the source of the constraints that make an agent behave like the brand it represents**.

---

## What AX design needs — and where the BOS provides it

Cramer identifies five new design assets required for agent-ready products. The BOS already generates the value foundation each of them requires:

### Policies
**AX definition**: Governance frameworks defining what an agent may, must, and must not do. Spending limits, escalation triggers, override conditions, approval gates.

**Where the BOS generates this**: The behavioral matrix (Allowed / Sensitive / Prohibited) from the [Open Ethical Layer](./07_open-ethical-layer.md) and the Brand Governance Playbook are Policies. The Refusal Register documents every boundary the brand has deliberately chosen to enforce. These are not technical configurations: they are the output of deliberative governance that the Synthesis Circle has validated against the brand's radical values.

> Without the BOS value process, Policies are contractual conventions. With it, they are expressions of identity.

### Skills
**AX definition**: Packaged instructions that teach an agent how to use a product correctly — structured, context-efficient guidance loaded when a specific task needs to be accomplished.

**Where the BOS generates this**: The Specula Agent (Layer 07 · INTERFACE) is a brand-configured skill: it carries the brand's DNA, knows its scenarios, has access to the Decision Memory and Refusal Register, and is onboarded through real decision cases (see [Agent Onboarding](../workshops/onboarding-agent.md)). It is not a generic assistant: it is a value-carrying interlocutor.

### Contracts
**AX definition**: Operation specifications beyond API endpoints — stable names, typed inputs/outputs, pre/post-conditions, explicit side effects, rollback procedures, blast radius classification.

**Where the BOS generates this**: The [specula-framework](https://github.com/oddtitoreal/specula-framework) provides the runtime contracts (JSON schemas, phase specifications, artifact envelopes) that make BOS outputs machine-readable and agent-operable. The behavioral matrix maps directly to permission scopes and side-effect declarations.

### Evaluation sets
**AX definition**: Golden tasks, regression tests, acceptance criteria — the agent equivalent of usability testing.

**Where the BOS generates this**: The Agent Onboarding workshop uses real past decisions as evaluation cases: would the agent have signaled coherence or drift? Divergences between agent responses and actual decisions become the calibration dataset. This is not usability testing: it is value coherence testing.

### Runbooks
**AX definition**: Structured recovery paths for failure — what happened, why, and what to try next.

**Where the BOS generates this**: The Guardian Loop and Re-Speculation trigger define the recovery protocol at the brand identity level: when signals diverge for two consecutive cycles, the system proposes re-entry at the layer closest to the origin of the problem. This is a runbook for identity drift, not just technical failure.

---

## The missing layer Cramer names but doesn't build

Cramer's framework is precise about what AX design assets look like technically. What it does not address is how an organization decides *what goes into* those assets — particularly Policies.

Policies that emerge from legal review are compliance documents. Policies that emerge from a deliberative value process are identity artifacts. The difference is not semantic: it determines whether an AI agent, when operating autonomously, behaves in ways the brand would actually endorse — or simply in ways no one explicitly prohibited.

**The BOS is the process that generates authentic Policies.**

The Synthesis Circle deliberation, the Brand Archaeology workshop, the Value Stress Test, and the Refusal Register produce exactly what Floridi's AI ethics principles call for: values that are explicit, verifiable, and contestable over time. Not because the BOS was designed for AI governance, but because it was designed to make identity coherent under pressure — and that is precisely what autonomous agents require of the brands they represent.

---

## Practical implications: what to build

If your organization is moving into AX — or already has agents acting on its behalf — the BOS outputs map directly to the technical layer:

| BOS artifact | AX design asset | How to use it |
|---|---|---|
| Behavioral matrix (Allowed / Sensitive / Prohibited) | Policy specification | Translate directly into agent permission scopes and constraint rules |
| Refusal Register | Negative policy constraints | Each STOP entry becomes an explicit prohibition in the agent's operating contract |
| Decision Principles | Policy rationale | Document *why* each constraint exists — agents that understand the reasoning handle edge cases better |
| Specula Agent configuration | Skill definition | The prompt architecture and memory structure from Agent Onboarding become the agent's skill package |
| Brand Memory | Agent context | The DNA, scenarios, and decision history inform the agent's responses when navigating ambiguous situations |
| Guardian Report | Evaluation baseline | Periodic coherence checks measure whether agent behavior still reflects current brand identity |

---

## A note on autonomy and governance

The AX era does not remove the need for human governance — it makes it more urgent. Cramer's fundamental rule and Specula's are the same:

> **The agent suggests and executes. The human decides what is permissible.**

Re-Speculation, the trigger that reboots a BOS cycle when reality diverges from imagined futures, is always a human decision. The system signals the need. The Synthesis Circle deliberates. The Brand Alchemist holds the memory.

This is not a limitation of the system. It is the architecture of responsible agency.

---

*Versione italiana: [09_agent-experience.it.md](./09_agent-experience.it.md)*

*References: Cramer, M. (2026). "Your New User Is AI Itself." · Floridi, L. et al. (2018). "An Ethical Framework for a Good AI Society." Minds and Machines, 28(4).*
