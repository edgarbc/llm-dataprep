# llm-dataprep


[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)
[![Built with uv](https://img.shields.io/badge/Built%20with-uv-%23f7df1e)](https://github.com/astral-sh/uv)

A lightweight utility to automate dataset preparation using LLMs and kaggle integration
---

## 🚀 Features
- 🔍 Automated Kaggle dataset exploration and downloading
- 🤖 LLM-powered dataset processing and preparation
- 📊 Customizable data transformation pipelines
- 🔄 Integration with popular data science workflows
- 📦 Built using [`uv`](https://github.com/astral-sh/uv) for fast, modern Python dependency management

## Directory structure

```
llm-dataprep/
├── .venv/                  # Virtual environment (already exists)
├── .git/                   # Git repository (already exists)
├── notebooks/             # Jupyter notebooks for exploration (already exists)
├── src/                   # Main source code
│   ├── __init__.py
│   ├── kaggle/           # Kaggle integration module
│   │   ├── __init__.py
│   │   ├── client.py     # Kaggle API client
│   │   └── downloader.py # Dataset download utilities
│   ├── llm/              # LLM processing module
│   │   ├── __init__.py
│   │   ├── processor.py  # LLM data processing
│   │   └── prompts.py    # LLM prompt templates
│   └── pipeline/         # Data transformation pipeline
│       ├── __init__.py
│       ├── transformers.py
│       └── validators.py
├── tests/                # Test suite
│   ├── __init__.py
│   ├── test_kaggle/
│   ├── test_llm/
│   └── test_pipeline/
├── data/                 # Data directory
│   ├── raw/             # Raw downloaded datasets
│   ├── processed/       # Processed datasets
│   └── .gitkeep
├── config/              # Configuration files
│   ├── __init__.py
│   └── settings.py      # Project settings and constants
├── docs/               # Documentation
│   ├── api/
│   └── examples/
├── main.py             # Main entry point (already exists)
├── pyproject.toml      # Project configuration (already exists)
├── README.md           # Project documentation (already exists)
├── LICENSE             # License file (already exists)
└── .python-version     # Python version file (already exists)
```






## 📋 Prerequisites

- Python 3.10 or higher
- Kaggle API credentials
- (Optional) OpenAI API key for LLM processing

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/llm-dataprep.git
cd llm-dataprep
```

2. Create and activate a virtual environment using uv:
```bash
uv venv
source .venv/bin/activate
```

3. Install dependencies:
```bash
uv pip install -e ".[dev]"
```

4. Set up Kaggle credentials:
   - Go to your Kaggle account settings
   - Create a new API token
   - Save the `kaggle.json` file in `~/.kaggle/`

## 🎯 Usage