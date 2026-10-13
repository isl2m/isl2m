# Islam Fathy

Software engineer focused on developer tooling, editor architecture, and localization systems.

---

### 📌 About

I build tools that solve practical friction points in modern development workflows. My work often involves IDE internals, TypeScript/Node.js tooling, and bidirectional text rendering (BiDi) in developer environments.

---

### 🚀 Featured Project

#### [RightFlow](https://github.com/isl2m/rightflow) — Universal RTL & BiDi Engine for AI Coding IDEs
*An open-source extension and runtime engine bringing native right-to-left layout and natural BiDi flow to modern AI IDEs and code editors.*

- **Why it was built:** Modern AI coding environments (Antigravity IDE, Cursor, GitHub Copilot, Windsurf) break Arabic, Hebrew, and Persian text formatting in chat windows, prompts, and planning artifacts—scrambling punctuation and reversing mixed technical lines.
- **Technical Highlights:**
  - **Zero-Dependency Heuristic Engine:** Custom bidirectional sentence parser that accurately detects Arabic sentences even when starting with Latin technical terms (`Docker`, `TypeScript`, `API`).
  - **Code Isolation:** Strict boundary enforcement ensuring code snippets and inline backticks maintain 100% LTR formatting.
  - **Cross-Platform Lifecycle Patching:** Safe, idempotent workbench patcher with automated backups and checksum synchronization across Windows, macOS, and Linux.
  - **Production CI Matrix:** Automated test suites verified on GitHub Actions across Ubuntu, Windows, and macOS runners.
- **Availability:**
  - [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=isl2m.rightflow)
  - [Open VSX Registry](https://open-vsx.org/extension/isl2m/rightflow)
  - [GitHub Releases](https://github.com/isl2m/rightflow/releases)

---

### 🛠️ Technical Focus & Tooling

- **Languages:** TypeScript, JavaScript, Python
- **Ecosystems:** VS Code Extension API, Electron, Node.js, Monaco Editor
- **Practices:** Cross-platform CLI tooling, Test-driven development, CI/CD automation (GitHub Actions)

---

### 📬 Connect

- **VS Code Publisher:** [@isl2m](https://marketplace.visualstudio.com/publishers/isl2m)
- **GitHub:** [@isl2m](https://github.com/isl2m)
- **Issues & Discussions:** [RightFlow Issue Tracker](https://github.com/isl2m/rightflow/issues)
