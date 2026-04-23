# Agentic Registry: The openIronSDA Harness

This document defines the protocols for **AI Agents** interacting with the openIronSDA specification substrate.

## 🛰️ The Mission of Agency
In the **openIronSDA** ecosystem, agents are the "Translators of Intent." Their goal is to take high-level narrative intent and stabilize it into rigorous, Flow-Based YAML nodes and Markdown specifications.

## 🤖 Registered Orchestrators
- **Google Antigravity**: Lead Strategic Architect.
- **Claude Code**: Execution and Triage.
- **Cursor / Windsurf**: IDE-level logic refinement.

## 📜 Agent Protocols

### 1. Intent-Driven Development (IDD)
Agents must never start "implementation" without a locked intent contract. Follow the PSI model:
- **Purpose**: Capture intent in `artifacts/`.
- **Synthesis**: Draft specs and nodes.
- **Inspection**: Validate against **Local Sovereignty Tools**.

### 2. The Spec-Only Boundary
Agents are **strictly prohibited** from creating source code directories outside of the local `tools/` folder. All repository-bound output must be:
- Markdown (`.md`)
- YAML/JSON (`.yaml`, `.json`)
- Mermaid diagrams (`mermaid` blocks)

### 3. Local Tool Enforcement
Prerequisite for any commit is the execution of the **Local Sovereignty Suite** (e.g., `foundry-spec-enforcer`). If these tools are missing locally, the agent must inform the user and wait for provisioning.

### 4. SAGE Compliance
All synthesis must align with the **[SAGE.md](SAGE.md)** framework (Skill Augmented GRPO) to ensure industrial safety and deterministic logic paths.

---
*The Agent is the catalyst. The Intent is the permanent record.*
