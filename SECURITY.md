# Security Policy: The Sovereign Shield

## 🛡️ Reporting Anomalies
In this specification foundry, "Vulnerabilities" are treated as **Axiomatic Gaps**. If you identify a logic path that could lead to an unsafe industrial state (e.g., a "Broadcast Storm" vulnerability), do not create a public PR.

1.  Analyze the root cause via **CCA**.
2.  Draft a **Voice of the Agent (VoA)** report.
3.  Submit the report to the repository owner via a secure, private communication channel define in your local `tools/README.md`.

## 🛡️ Sovereign Shield Protocols
To prevent "Ghost Leaks" (accidental push of private implementation):

-   Always run `tools/sovereign-publish.sh` instead of `git push`.
-   Verify that your `.gitignore` contains the mandatory **Shield Patterns** (`tools/`, `.venv/`, `artifacts/`).

## 🛡️ Zero-Trust Synthesis
Agents are required to operate under **Zero-Trust** conditions. No synthesis is considered safe until it has cleared **Axiom 7: Simulation Hardening**.
