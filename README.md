# agent_project_generator

````markdown
# 🧠 AI Project Generator

This is a Python-based AI agent that automatically generates entire project structures and codebases from a natural language prompt.  
It uses OpenAI's GPT-4 to generate working code, organize files and folders, and provide instructions for running the project.

---

## 🚀 Features

- Accepts natural language project descriptions
- Generates full directory + file structure
- Writes complete, functional code for each file (no TODOs or placeholders)
- Provides step-by-step instructions to run the project
- Creates everything in a `generated_project/` directory

---

## 🛠 Requirements

- Python 3.8+
- OpenAI API key (GPT-4 access)

Install dependencies:
```bash
pip install openai
````

Set your API key:

```bash
export OPENAI_API_KEY=your-key-here
```

---

## 🧪 How to Use

Run the agent:

```bash
python project_agent.py
```

Then, enter a prompt describing your project. For example:

> "Build a CLI tool that fetches the weather using OpenWeatherMap API."

This will:

1. Plan the project architecture
2. Create a directory `generated_project/`
3. Fill it with runnable code
4. Print instructions on how to run the project

---

## 📁 Output Structure Example

```
generated_project/
├── app.py
├── utils/
│   └── weather_fetcher.py
└── README.md
```

---

## ✅ Sample Prompts

* "Create a Flask app that lets users submit and view notes"
* "Build a CLI that renames all files to lowercase"
* "Create a Streamlit dashboard to visualize a CSV"
* "Build a Python script that scrapes headlines from Hacker News"

---

## 🧙 Built With

* OpenAI GPT-4
* Python
* 🪄 Grimoire.dev Prompt Engineering

---

## ⚠️ Disclaimer

This tool generates files using GPT. Always review and test the code before deploying in production environments.

