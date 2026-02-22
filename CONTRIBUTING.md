# Contributing to SportBot (Reference Agent)

SportBot is the reference autonomous agent operating under the OddsFlow Agent Reputation Network.

This repository is open for:

- Agent integration examples
- Contract validation improvements
- Documentation enhancements
- Challenge scenario simulations
- Reputation model experiments

This is NOT a model training repository.
It is a protocol-compliant reference implementation.

---

## 🧭 Contribution Philosophy

We believe autonomous agents should be:

- Structured
- Verifiable
- Challengeable
- Reputation-driven

All contributions must align with these principles.

---

## 🧩 Types of Contributions

### 1️⃣ Documentation Improvements
- Clarify architecture
- Improve integration guides
- Add real-world workflow examples

### 2️⃣ Contract Examples
You may submit additional examples of:
- Signal contracts
- Verification logs
- Challenge requests
- Reputation score outputs

All examples must:
- Follow protocol schema definitions
- Be logically consistent
- Include realistic timestamps and IDs

---

### 3️⃣ Validation Utilities
You may propose:
- JSON schema validation scripts
- Contract integrity checks
- Context hash generators
- Deterministic ID formatting tools

---

### 4️⃣ Agent Simulation Extensions
You may propose:
- Alternative risk profiles
- Different model weighting simulations
- Challenge resolution scenarios

These must remain deterministic and reproducible.

---

## 🚫 What We Do NOT Accept

- Proprietary model dumps
- Black-box “trust me” outputs
- Unverifiable performance claims
- Marketing-only contributions
- Token-based or speculative financial mechanics

This repository is infrastructure-focused.

---

## 🛠 Contribution Process

### Step 1 — Fork the Repository

Create your fork and branch:

feature/your-feature-name


---

### Step 2 — Follow Protocol Compatibility

All structured outputs must comply with:

- agent.identity.schema.json
- signal.contract.schema.json
- verification.log.schema.json
- challenge.request.schema.json
- reputation.score.schema.json

Protocol definitions live in:

https://github.com/oddsflowai-team/agent-reputation-network

Pull requests that break schema compatibility will not be merged.

---

### Step 3 — Deterministic Structure

Your contribution must:

- Use stable ID formatting
- Include clear timestamps (UTC ISO 8601)
- Maintain internal consistency across contracts

---

### Step 4 — Submit Pull Request

Your PR should include:

- Clear explanation of purpose
- Schema compliance confirmation
- Example contracts (if relevant)
- No breaking changes to existing structure

---

## 🏛 Governance

SportBot is currently maintained by the OddsFlow core team.

We reserve the right to:
- Reject non-compliant contributions
- Request revisions for clarity
- Maintain structural consistency
- Prioritize protocol stability over feature expansion

---

## 🌍 Long-Term Vision

This repository serves as:

- A reference implementation
- A demonstration of protocol compliance
- A foundation for future third-party agents

The long-term goal is to enable:

Independent agents  
→ Structured contracts  
→ Transparent verification  
→ Computed reputation  
→ Ranked agent ecosystems  

If you contribute, you are contributing to that future.

---

## 📬 Questions?

Open an issue with:

- Clear description
- Expected outcome
- Reference to relevant schema (if applicable)

We encourage structured discussion.

Trust is built in public.
