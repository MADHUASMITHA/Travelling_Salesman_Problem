# Project Usage Guide

This repository contains a Jupyter Notebook implementing Artificial Intelligence search and optimisation techniques to solve the Travelling Salesman Problem (TSP).  
Follow the instructions below to set up and run the project successfully.

---

## Prerequisites
- Python 3.x
- Jupyter Notebook or JupyterLab

---

## Required Libraries
Ensure the following Python libraries are installed:
- numpy
- pandas
- matplotlib
- scipy

Install all dependencies using:
```
pip install numpy pandas matplotlib scipy
```

---

## Repository Structure
```
├── Code.ipynb              # Main Jupyter Notebook (implementation + analysis)
├── cities.csv              # Original dataset (50 cities)
├── cities_cleansed.csv     # Preprocessed dataset
├── README.md               # Project usage instructions
├── results/                # Saved routes and result tables
└── figures/                # Generated plots and visualisations
```

---

## How to Run the Project

1. **Download or Clone the Repository**
   ```
   git clone <repository-url>
   ```
   or download and extract the ZIP file.

2. **Navigate to the Project Directory**
   ```
   cd <project-folder>
   ```

3. **Start Jupyter Notebook or JupyterLab**
   ```
   jupyter notebook
   ```
   or
   ```
   jupyter lab
   ```

4. **Open the Notebook**
   - Open `Code.ipynb` from the Jupyter interface.

5. **Run the Notebook**
   - Execute all cells sequentially from top to bottom.
   - Do not skip cells, as later steps depend on earlier outputs.

---

## Data Usage
- Ensure `cities.csv` is present in the project root directory.
- Do not rename files unless paths are updated in the notebook.
- The notebook performs data cleansing, optimisation, and evaluation automatically.

---

## Output
- Best routes for Simulated Annealing and Genetic Algorithm are saved in the `results/` folder.
- Performance comparison tables are stored as CSV files.
- Visualisations are generated and saved in the `figures/` folder.
- Console output displays distance metrics and statistical test results.

---

## Reproducibility Notes
- Random seeds are set within the notebook to support reproducible results.
- Use consistent library versions for comparable performance.

---

## Execution Tips
- Run the notebook in a clean Python environment.
- Restart the kernel and re-run all cells if unexpected errors occur.
- Allow the notebook to complete execution for all city sizes (10–50).

---

