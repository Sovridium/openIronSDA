# Repository Configuration Axioms

To maintain the **Substrate Integrity** and **Sovereign Status** of **openIronSDA**, the following GitHub settings are mandated.

## 🏁 Required GitHub Configuration

### 1. General Settings
- **Template repository**: **ENABLED**.
- **Discussions**: **ENABLED**. Source for **VoC** and **CAB** strategic feedback.
- **Issues**: **ENABLED**. Tracking for **Strategic Intents** and **Anomalies**.
- **Wikis**: **DISABLED**. All documentation resides in version-controlled `.md` files.

### 2. Convergence Logic (Merging)
- **Allow squash merging**: **ENABLED**.
- **Allow rebase merging**: **DISABLED**. Atomic intent-pushes only.
- **Automatically delete head branches**: **ENABLED**.

### 3. Branch Protection (`main`)
- **Require a pull request before merging**: **ENABLED**.
- **Require signed commits**: **ENABLED**. Crucial for Sovereign Proof.
- **Lock branch**: **DISABLED**.
- **Restrict pushes**: **ENABLED**. Pushes must originate from the verified local substrate.

### 4. GitHub Pages
- **Deployment**: **ENABLED**. Host from `/docs` folder.

---
*The settings are the bolts of the vault. Do not loosen them.*
