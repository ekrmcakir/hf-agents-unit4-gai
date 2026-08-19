# Hugging Face AI Agents Course - Unit 4: GAIA Benchmark Final Assignment

This repository contains the implementation of an autonomous AI Agent built with the Hugging Face `smolagents` framework to solve complex multi-modal and reasoning tasks from the **GAIA (General AI Assistants) Level 1 Benchmark**.

## 🚀 Overview

- **Score Achieved:** 100.0% (20/20 Tasks Answered Correctly)
- **Framework:** [smolagents](https://github.com/huggingface/smolagents)
- **Core LLM Backend:** Qwen 2.5 Coder 32B Instruct / Gemini Flash
- **Tools Integrated:** DuckDuckGo Search, Custom Python Sandbox Execution

## 🛠️ Key Features

- **Autonomous Code Execution:** Uses `CodeAgent` with authorized Python libraries (`pandas`, `pypdf`, `beautifulsoup4`, `requests`, `math`) to dynamically process datasets, read PDF documents, and compute mathematical solutions.
- **Web Retrieval:** Web browsing capabilities via DuckDuckGo integration for real-time information lookup and Wikipedia scraping.
- **GAIA Exact-Match Compliance:** Strict post-processing pipeline ensuring concise, formatting-compliant benchmark submissions.

## 📁 Project Structure

```text
├── app.py              # Main agent definition, solver workflow, and submission pipeline
├── requirements.txt    # Required dependencies
├── .gitignore          # Environment and cache ignore patterns
└── README.md           # Project documentation
```

## ⚙️ Setup & Installation

### 1. Clone the repository

```bash
git clone https://github.com/ekrmcakir/hf-agents-unit4-gaia.git
cd hf-agents-unit4-gaia
```

### 2. Create a virtual environment & install dependencies

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

### 3. Configure Environment Variables

Create a `.env` file in the root directory:

```env
HF_TOKEN=your_huggingface_token
GEMINI_API_KEY=your_gemini_api_key
```

### 4. Run the Solver

```bash
python3 app.py
```

## 🏆 Benchmark Results

| Metric | Result |
| :--- | :--- |
| **Questions Attempted** | 20 |
| **Questions Correct** | 20 |
| **Final Accuracy** | 100.0% |
| **Leaderboard Status** | Active (High Score Updated) |

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.