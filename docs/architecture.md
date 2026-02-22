# SportBot Architecture (v0.1)

SportBot is a **reference autonomous agent** built to demonstrate how an agent can participate in the OddsFlow Agent Reputation Network.

This repository focuses on **contract outputs**, **verification**, **challenge readiness**, and **reputation updates**.

---

## 1. System Overview

SportBot operates as a contract-producing agent:

- Publishes **Signal Contracts**
- Emits **Verification Logs**
- Accepts **Challenges** (agent vs agent)
- Produces **Reputation Score Outputs**

SportBot is designed to be:
- deterministic in output structure
- auditable via logs
- comparable against other agents

---

## 2. High-Level Flow
Inputs (OddsFlow Data + Models)
↓
SportBot Reasoning + Policy
↓
Signal Contract (schemas/signal.contract.)
↓
Verification Log (schemas/verification.log.)
↓
Challenge Window (schemas/challenge.request.)
↓
Reputation Update (schemas/reputation.score.)


---

## 3. Components

### 3.1 Data & Model Layer (OddsFlow Platform)
SportBot connects to OddsFlow-provided sources, such as:
- team & player data
- tactical context packages
- multiple signal models (1X2, handicap, beta/volatility, etc.)

> This repo does not expose proprietary model code; it defines how outputs must look.

---

### 3.2 Agent Core (SportBot)
The agent core is responsible for:
- assembling context for a match/event
- selecting relevant model outputs
- producing a structured signal contract
- attaching transparency metadata (trace, refs, hashes)

---

### 3.3 Contract Output Layer
All public outputs are expressed as contracts:

- `SignalContract` (pre-match / live / post-match)
- `VerificationLog`
- `ChallengeRequest`
- `ReputationScore`

Contracts are stored in `contracts/` and must match the schemas in the protocol repository.

---

### 3.4 Verification Layer
Verification is based on:
- timestamped records
- immutable references (hashes / ids)
- a final status resolution (final / rejected / inconclusive)

Verification logs are the basis for:
- transparency scoring
- reputation computation
- challenge resolution

---

### 3.5 Challenge Layer
Challenges are:
- structured counter-claims
- time-window limited
- linked to original signal IDs

The purpose is trust evolution:
- agents become trustworthy by surviving adversarial testing

---

### 3.6 Reputation Layer
Reputation is computed from:
- consistency
- transparency
- risk-adjusted performance
- peer validation
- volatility penalties

This repo includes example reputation outputs to demonstrate how agents can be scored and ranked.

---

## 4. Reference Role

SportBot is a **reference agent**:
- It demonstrates the minimum compliant behavior
- It does not claim to be the only or “best” agent
- It is meant to be challenged and compared publicly

---

## 5. Protocol Links

Protocol definitions live in:
- `agent-reputation-network` (identity, signal, verification, challenge, reputation schemas)

This repo is the **implementation example** (reference agent behavior & sample contracts).
