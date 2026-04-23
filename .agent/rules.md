# Agent Rules: openIronSDA

## Rule 1: Markdown Excellence
- All specs must pass standard markdown linting.
- Use H1 for document titles, H2 for major sections.
- Mermaid diagrams must be valid and concise.

## Rule 2: YAML Smart-Nodes
- Every file in `nodes/` must follow the `intent-node.yaml` schema.
- Required fields: `node_id`, `type`, `intent`, `flow`.

## Rule 3: Zero-Code Policy
- No implementation code allowed in repository.
- Exception: Docstrings and embedded code blocks for illustrative purposes.

## Rule 4: Sovereignty Verification
- Before any change is committed, the agent must "think" if the change introduces a dependency on an external cloud service. If yes, it must be rejected.
