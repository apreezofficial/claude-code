# 🚀 Claude Code Python Port (Research Workspace)

> ⚡ **Experimental Python re-implementation workspace inspired by the Claude Code architecture exposure (March 31, 2026).**

This repository is a **Python-first research workspace** focused on understanding and rebuilding agent-style coding systems inspired by the architecture that surfaced during the **Claude Code source exposure event**.

The repository **no longer tracks the exposed snapshot**.  
Instead, it focuses on **clean Python reimplementation work, architectural exploration, and tooling research**.

⭐ **If you find this interesting, consider starring the repo to support the project.**

---

# 🔥 Why This Repository Exists

On **March 31, 2026**, a widely discussed event exposed internal architecture related to **Claude Code**, an AI coding tool.

While studying the architecture, several interesting patterns emerged:

- agent command orchestration
- tool invocation pipelines
- task-based workflow coordination
- query-driven reasoning loops

Rather than keeping the exposed code snapshot, this repository now focuses on:

✔ **clean Python reimplementation research**  
✔ **architecture exploration**  
✔ **AI coding tool workflow design**  
✔ **agent tooling experiments**

---

# 🧠 Project Goals

This repository explores how modern **AI coding agents** might be structured internally.

Areas currently being studied:

- command orchestration
- task pipelines
- query execution loops
- tool invocation frameworks
- subsystem manifest generation
- modular agent architecture

The goal is **not to recreate the original system**, but to explore **ideas inspired by the architecture patterns observed during analysis**.

---

# 📂 Repository Structure

```

.
├── src/                                # Python porting workspace
│   ├── **init**.py
│   ├── commands.py                     # command metadata layer
│   ├── main.py                         # CLI entrypoint
│   ├── models.py                       # system dataclasses
│   ├── port_manifest.py                # workspace manifest generator
│   ├── query_engine.py                 # workspace analysis engine
│   ├── task.py                         # task orchestration primitives
│   └── tools.py                        # tool wiring layer
│
├── tests/                              # Python verification suite
│
├── assets/omx/                         # OmX workflow screenshots
│
└── README.md

````

---

# ⚙️ Python Workspace Overview

The current Python workspace includes the following core components.

### `port_manifest.py`

Generates a structured summary of the current Python workspace including:

- subsystems
- modules
- port progress
- architecture overview

---

### `models.py`

Defines internal system models using **Python dataclasses**.

Includes representations for:

- subsystems
- modules
- task states
- port tracking structures

---

### `commands.py`

Contains the **command metadata layer** used for describing agent commands and execution behavior.

---

### `tools.py`

Defines tool wiring structures that allow the agent workspace to invoke external or internal functionality.

---

### `query_engine.py`

Provides the **analysis layer** that renders summaries of the Python port workspace.

Used for:

- system inspection
- architecture summaries
- subsystem listing

---

### `main.py`

CLI entrypoint that exposes repository utilities.

---

# 🚀 Quickstart

Clone the repository:

```bash
git clone https://github.com/apreezofficial/claude-code.git
cd claude-code
````

---

## Generate Python Port Summary

```bash
python3 -m src.main summary
```

---

## Print Workspace Manifest

```bash
python3 -m src.main manifest
```

---

## List Current Subsystems

```bash
python3 -m src.main subsystems --limit 16
```

---

## Run Verification Tests

```bash
python3 -m unittest discover -s tests -v
```

---

# 🧩 Research Focus

This project is currently exploring patterns used in **modern AI coding assistants**, including:

* agent command systems
* tool execution loops
* reasoning pipelines
* modular coding agents
* code generation workflows

The repository acts as a **sandbox for experimenting with these architectures in Python**.

---

# 🧠 AI Workflow

The repository restructuring process was assisted by **AI-driven development workflows**.

Tools used include:

* Codex
* OmX (oh-my-codex)
* structured multi-agent review pipelines

---

# 🧪 Built With OmX (oh-my-codex)

This repository was partially orchestrated using **OmX**, a workflow system created by **Yeachan Heo**.

Repository:
[https://github.com/Yeachan-Heo/oh-my-codex](https://github.com/Yeachan-Heo/oh-my-codex)

OmX enables:

* parallel agent review
* execution pipelines
* multi-agent orchestration

---

### OmX workflow screenshots

![OmX workflow screenshot 1](assets/omx/omx-readme-review-1.png)

*Ralph/team orchestration view during documentation review.*

---

![OmX workflow screenshot 2](assets/omx/omx-readme-review-2.png)

*Split-pane verification and review workflow.*

---

# 📚 Related Essay

An earlier essay discussing legal and ethical questions around AI reimplementation can be found here:

**Is legal the same as legitimate: AI reimplementation and the erosion of copyleft**

[https://writings.hongminhee.org/2026/03/legal-vs-legitimate/](https://writings.hongminhee.org/2026/03/legal-vs-legitimate/)

The essay was written **before the March 31, 2026 architecture exposure event**, but it discusses relevant philosophical questions.

---

# ⭐ Support The Project

If you find this repository useful or interesting:

⭐ Star the repository
🍴 Fork it
🧠 Share insights or improvements

GitHub:

[https://github.com/apreezofficial/claude-code](https://github.com/apreezofficial/claude-code)

---

# ⚠️ Disclaimer

This repository:

* **does not contain the exposed Claude Code snapshot**
* **does not claim ownership of Anthropic intellectual property**
* **is not affiliated with Anthropic**

The project exists solely as a **Python research workspace exploring agent-style coding architectures**.

---

# 🧭 Future Roadmap

Planned areas of exploration include:

* agent planning loops
* tool orchestration frameworks
* code reasoning pipelines
* autonomous coding agents
* architecture visualizations

---

**Experimental AI architecture research in progress.**
