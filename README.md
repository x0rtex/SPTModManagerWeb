# SPT Mod Manager Web

A web-based mod manager for **SPT-AKI** (Escape from Tarkov singleplayer).  
It’s designed to run on a local or remote server, allowing mod management directly through a browser.

---

## 🚀 Features (Planned)

- View installed mods
- Download, update, or delete mods
- Authentication for secure remote access

---

## ⚙️ Setup Instructions

### 1. Prerequisites

- Python 3.12+  
- [`uv`](https://docs.astral.sh/uv/) (package manager)  

```bash
pip install uv
```

### 2. Initialize and install dependencies

```
uv sync
```

### 3. Run the development server

```
uv run task dev
```

Then open your browser:

```arduino
http://localhost:8000
```
