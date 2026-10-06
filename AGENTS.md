# AGENTS.md

- 所有的回應都使用繁體中文。
- 專案語言為 Python，使用 conda 管理 Python 套件，環境名稱為 `iem_python`。
- Repo 是 greenfield：`README.md` 只有一行標題，尚無原始碼、manifest、測試或 CI。`.gitignore` 是標準 Python 範本，但目前尚無 `pyproject.toml`、`requirements*.txt` 或工具鏈設定。
- No verified build, test, lint, or run commands exist. Do not invent any. Check for manifests/scripts before proposing commands.
- When scaffolding the project: pick the toolchain explicitly with the user, then update this file with the real entrypoints and exact verification commands.
