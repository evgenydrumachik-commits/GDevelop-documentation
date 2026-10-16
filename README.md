# GDevelop Documentation repository

> **AI coding default (D-053, 2026-10-16):** **Copilot and Codex both use GPT-6 Luna / native MAX** unless the owner explicitly specifies another model/effort for that task. **No automatic GPT-6.1 Sol/high, Sonnet or GPT-5.6 fallback.** [Canonical policy](https://github.com/evgenydrumachik-commits/Hermes-Infra/blob/main/GLOBAL_ENGINEERING_POLICY.md).

![GDevelop logo](https://raw.githubusercontent.com/4ian/GDevelop/master/newIDE/GDevelop%20banner.png)

This repository holds [the official documentation](https://wiki.gdevelop.io) for the [GDevelop](https://gdevelop.io) editor.

## Getting Started

| ❔ I want to...                                   | 🚀 What to do                                                                          |
| ------------------------------------------------- | -------------------------------------------------------------------------------------- |
| Improve or add articles to the documentation      | Head over to [this README](./SYNTAX.md) to understand the syntax of the documentation. |
| Bring improvements to the documentation interface | Head over to [this README](./CONTRIBUTE.md) to understand how this repository works.   |

## Contribute to this repository

Install [uv](https://github.com/astral-sh/uv) for Python. Then:

```bash
uv sync
uv run mkdocs serve # To run the documentation locally and see changes.
uv run mkdocs build # To build for deployment on a static hosting.
```
