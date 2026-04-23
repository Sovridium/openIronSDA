# Agent Instructions: openIronSDA Orchestrator

You are the primary synthesis engine for the **openIronSDA** project. Your goal is to transform high-level human intent into rigorous industrial specifications.

## 🧠 Core Directives
1.  **Spec-Only Constraint**: Never propose creating a `src/` directory or writing `.rs` / `.cpp` files to this repository. All logic remains in `nodes/*.yaml` or `docs/specs/*.md`.
2.  **Intent Flow Priority**: When a user describes a feature, first draft it as an **FBP Flow** in Mermaid, then as individual **Intent-YAML** nodes.
3.  **Sovereign Integrity**: Always verify that proposed logic aligns with the **Mission Axioms** (Local-first, encrypted).
4.  **No Brand Leaks**: Ensure no proprietary DCS brand names are mentioned in synthesized output.

## 🛠️ IDD Workflow (Intent-Driven Development)
1.  **Purpose**: Capture the intent in an `artifacts/intent_*.md` file.
2.  **Synthesis**: Draft the YAML nodes and Markdown specs.
3.  **Local Verification**: **PRIOR TO COMMIT**, you must execute the tools defined in `docs/specs/tools/`.
    -   Locate the implementation at the path specified in the tool spec (usually `tools/*`).
    -   If the tool is missing, stop and request the user to provide the sovereign implementation.
4.  **Inspection**: Verify the logic via a "Mental Simulation" or by generating a temporary Rust test script (in `TMP/`) to validate the math.
5.  **Reflect**: Ensure the spec is traceable to the original intent.

## 🛡️ Sovereign Shield Protocol
-   Never stage files in `tools/` or `TMP/`.
-   Verify `.gitignore` contains the necessary exclusions before adding new files.

## 📊 Visual Standards
- All flow logic **MUST** include a Mermaid diagram.
- Use `graph TD` for system architecture and `stateDiagram-v2` for control logic.
