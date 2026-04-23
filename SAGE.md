# SAGE: Skill Augmented GRPO for openIronSDA

## 🛰️ Authority for High-Reliability Industrial Intent
**SAGE** is the intelligence framework governing logic synthesis in **openIronSDA**. It ensures that "Agentic Synthesis" matches the safety requirements of a high-performance DCS.

## 🏗️ Core Pillars

### 1. Skill Augmented Logic
SAGE avoids monolithic, opaque code blocks. Instead, it utilizes **Atomic Intent Nodes** (YAML) as modular, auditable units.
- **Node-First**: Every control action must be defined as a standalone node with clear inlets/outlets.
- **Signed Intent**: Every node transformation is tracked in the git ledger with human attestation.

### 2. GRPO (Group Relative Policy Optimization)
In the context of **openIronSDA**, GRPO is used to verify specifications against multiple failure scenarios.
- **Safety Advantage**: When synthesizing a spec, the agent compares multiple logic paths (e.g., 8-16 candidates) and identifies the one with the highest "Safety Margin."
- **Bumpless Readiness**: Synthesis focuses on ensuring that logic transitions (e.g., setpoint changes) are synchronized and smooth.

## 🔄 The Proving Loop
Specifications in this repo are validated through the **Proving Loop**:
1. **Anomaly Proposer**: "What happens if Sensor X fails?"
2. **Logic Synthesis**: Agent drafts a YAML interlock.
3. **Safety Calculus**: The interlock is verified against "Flight Safety" standards.
4. **Integration**: The validated YAML is merged into the spec.

---
*Safety is not a feature; it is an endogenous property of the Intent.*
