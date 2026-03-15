# Prompt Analyzer

A simple Python project that analyzes a user prompt and provides feedback to improve its clarity and usefulness.

This project demonstrates how small utility programs can help improve the quality of prompts used with AI tools.

---

## Project Objective

The goal of this project is to create a small Python program that checks a prompt and gives suggestions to make it clearer and more effective.

Prompt quality is very important when working with AI systems. A well-written prompt helps AI generate better responses.

---

## What This Project Does

The program analyzes a prompt and checks whether it:

* is **too short**
* contains **clear action words** (like explain, write, summarize)
* includes **context**
* asks for an **example**

After analyzing the prompt, the program prints feedback to help improve it.

---

## Project Structure

prompt-analyzer/
│
├── src/
│   ├── main.py
│   └── analyzer.py
│
├── .gitignore
├── README.md
└── requirements.txt

### File Description

**src/main.py**

This file runs the program. It asks the user to enter a prompt and prints the feedback returned by the analyzer.

**src/analyzer.py**

This file contains the logic that analyzes the prompt and checks for common prompt quality issues.

**.gitignore**

This file tells Git which files or folders should not be uploaded to GitHub.

Examples include:

* Python cache files
* virtual environments
* system files
* environment files

**requirements.txt**

This file normally lists Python packages required for the project.
This project currently does not require any external libraries.

**README.md**

This file explains the project so that anyone visiting the GitHub repository can understand what the project does and how to run it.

---

## How To Run The Project

### Step 1 — Open Terminal

Navigate to the project folder.

```
cd prompt-analyzer
```

### Step 2 — Move to the Source Folder

```
cd src
```

### Step 3 — Run the Program

```
python3 main.py
```

---

## Example Usage

When the program runs, it will display:

```
Prompt Analyzer
----------------------------------------
Enter a prompt to analyze:
```

Example input:

```
Explain AI
```

Example output:

```
Analysis Result:
- Prompt is too short. Add more context.
- Prompt may be missing context.
- Consider asking for an example.
```

Better prompt example:

```
Explain prompt engineering for beginners with one example
```

---

## Why This Project Is Useful

This project helps beginners learn:

* basic Python programming
* how to structure a Python project
* how prompt design affects AI responses
* how Git and GitHub are used in real development workflows
* how to write a proper README file for a project

---

## Learning Outcome

After completing this project, you will understand:

* how to create a structured Python project
* how to write a small utility program
* how to document a project using README.md
* how prompt quality can influence AI results

---
## Sample Learning Outcome

This project demonstrates how a simple Python utility can support better AI prompt writing.


Jagadeesh S
