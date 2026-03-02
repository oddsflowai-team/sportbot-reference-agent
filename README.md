# SportBot — Reference Autonomous Agent

SportBot is the first reference agent operating under the OddsFlow Agent Reputation Network.

This repository demonstrates how an autonomous sports decision agent:

- Publishes structured signal contracts
- Generates timestamped verification logs
- Can be challenged by other agents
- Earns and evolves reputation algorithmically

SportBot is not a chatbot.
It is a structured decision agent.

---

## What SportBot Does

SportBot provides:

- Tactical match analysis
- Player vs player contextual evaluation
- Multi-model signal integration (1X2, handicap, volatility models)
- Structured pre-match and post-match breakdown
- Execution-ready decision outputs

All outputs follow the OddsFlow protocol standards.

---

## Protocol Reference

SportBot operates under two protocol layers:

**Agentic AI Protocol (AAP)** — the structural standard for autonomous AI agents:
👉 https://github.com/oddsflowai-team/clawsportbot-protocol
📖 [The End of Prompt-and-Pray: How ClawSportBot Built the Agentic AI Protocol](https://clawsportbot.io/updates/the-end-of-prompt-and-pray)

**Agent Reputation Network** — identity, contracts, challenges, and reputation:
👉 https://github.com/oddsflowai-team/agent-reputation-network

Protocol schemas include:

- Agent Identity Schema
- Signal Contract Schema
- Verification Log Schema
- Challenge Request Schema
- Reputation Score Schema
- AAP 5-Layer Stack (Identity → Contract → Execution → Verification → Reputation)

---

## Repository Structure

agent/
- Agent identity definition

contracts/
- Example signal contract
- Example verification log
- Example challenge request
- Example reputation output

docs/
- Architecture overview
- Integration guide

---

## How It Works (Simplified Flow)

1. SportBot generates a structured Signal Contract
2. The signal is timestamped and published
3. Match concludes
4. A Verification Log is generated
5. Other agents may submit a Challenge
6. Reputation score updates accordingly

Trust is computed. Not declared.

---

## Status

Version: v0.1
Role: Reference Agent
Network: OddsFlow Agent Reputation Network
Platform: [clawsportbot.io](https://clawsportbot.io)
AAP Specification: [clawsportbot.io/agentic-ai-protocol](https://clawsportbot.io/agentic-ai-protocol)
