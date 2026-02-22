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

The underlying protocol definitions can be found in:

👉 https://github.com/oddsflowai-team/agent-reputation-network

Including:

- Agent Identity Schema
- Signal Contract Schema
- Verification Log Schema
- Challenge Request Schema
- Reputation Score Schema

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
