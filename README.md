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
uv pip install -r requirements.txt
```

4. Set up Kaggle credentials:
   - Go to your Kaggle account settings
   - Create a new API token
   - Save the `kaggle.json` file in `~/.kaggle/`

## 🎯 Usage