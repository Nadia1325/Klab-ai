# Python for AI – Assignment 1

## Project Overview

This repository contains my work for Assignment 1: Python for AI Warm-Up. The assignment demonstrates Python fundamentals, functions, NumPy, Pandas, and Matplotlib.

## Project Structure

```text
klab-ai-nadia/
│
├── .env.example
├── .gitignore
├── README.md
├── requirements.txt
│
├── notebooks/
│   └── assignment_1_python_ai.ipynb
│
├── src/
│
├── data/
│   ├── raw/
│   │   └── .gitkeep
│   └── processed/
│       └── .gitkeep
│
└── reports/
    ├── day01_chart.png
    └── day01_reflection.md
```

## 1. Create and Activate the Virtual Environment

On Windows PowerShell:

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
```

## 2. Install Dependencies

With the virtual environment activated:

```powershell
pip install -r requirements.txt
```

## 3. Run the Smoke Test

Run:

```powershell
python -c "import numpy, pandas, sklearn, matplotlib; print('all good')"
```

Expected output:

```text
all good
```

## 4. Open the Assignment Notebook

Start Jupyter:

```powershell
jupyter notebook
```

Then open:

```text
notebooks/assignment_1_python_ai.ipynb
```

Alternatively, the notebook can be opened directly in VS Code or another compatible editor.

## Reproducing the Assignment

1. Clone the repository.
2. Open a terminal in the repository folder.
3. Create the virtual environment.
4. Activate the virtual environment.
5. Install dependencies using `requirements.txt`.
6. Run the smoke test.
7. Open and run the assignment notebook from top to bottom.
