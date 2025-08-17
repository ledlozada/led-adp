# Awesome Data Philippines

## Local Development Guide

### Prerequisites
- Python 3.13 or higher
- [uv package manager](https://github.com/astral-sh/uv) installed

#### Installing uv (if not already installed)

**Linux/macOS:**
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

**Windows:**
```powershell
powershell -c "irm https://astral.sh/uv/install.ps1 | iex"
```

**Alternative (using pip):**
```bash
pip install uv
```

### 1. Clone the repository
```bash
git clone https://github.com/benhur07b/awesome-data-philippines-v2.git
```

### 2. Go to the project directory
```bash
cd awesome-data-philippines-v2
```

### 3. Create the virtual environment (can be skipped if you go directly to #4)
```bash
uv venv
```

### 4. Run the application
```bash
uv run mkdocs serve
```

The application is available on ```http://localhost:8000```.