# OReilly AutoML Book Notebooks

This repository contains companion notebooks for the O'Reilly book on automated machine learning. Each chapter notebook is self contained and can be run locally after installing the required packages.

## Setup

1. Create a virtual environment (optional but recommended):
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Data

A small example dataset is provided under `data/news_dataset.csv` for the Chapter 7 notebook. The Adult dataset used in Chapter 6 is automatically downloaded from the UCI repository when the notebook is executed.

## Running the Notebooks

Launch Jupyter and open any of the chapter notebooks:

```bash
jupyter notebook
```

Each notebook includes comments explaining the code samples from the book.
