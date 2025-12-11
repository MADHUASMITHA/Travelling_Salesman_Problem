# AI Search and Optimisation – Travelling Salesman Problem (TSP)

This project implements and evaluates Artificial Intelligence search and optimisation techniques to solve the Travelling Salesman Problem (TSP) using Python.

---

## 📌 Project Overview
The goal of this project is to find near-optimal routes for visiting a set of cities exactly once and returning to the starting point, while minimizing the total travel distance.

Two AI-based optimisation approaches are implemented and compared:
- **Simulated Annealing (SA)** – Single-solution based search
- **Genetic Algorithm (GA)** – Population-based evolutionary search

The project evaluates both methods based on solution quality, runtime efficiency, scalability, and statistical significance.

---

## 📂 Project Structure
```
.
├── Code.ipynb                    # Main Jupyter Notebook (implementation + analysis)
├── cities.csv                    # Original dataset (50 cities)
├── cities_cleansed.csv           # Cleansed dataset
├── results/
│   ├── scalability_results.csv   # Performance comparison results
│   ├── sa_best_route_*.txt       # Best SA routes
│   ├── ga_best_route_*.txt       # Best GA routes
│   └── report.md                 # Auto-generated summary report
├── figures/
│   ├── scalability_distance_SA_GA.png
│   ├── scalability_time_SA_GA.png
│   └── route_visualisations.png
└── README.md                     # Project documentation
```

---

## ⚙️ Requirements
Ensure the following libraries are installed:
```
numpy
pandas
matplotlib
scipy
```

Install dependencies using:
```bash
pip install numpy pandas matplotlib scipy
```

---

## ▶️ How to Run the Project

1. Place `cities.csv` in the project root directory.
2. Open the notebook:
```bash
jupyter notebook Code.ipynb
```
3. Run all cells sequentially.
4. The program will:
   - Clean the dataset
   - Execute SA and GA on multiple city sizes (10–50)
   - Save best routes and results
   - Generate plots and statistical analysis

---

## 📊 Evaluation Metrics
- Best distance found
- Average distance
- Standard deviation
- Average computation time
- Convergence behaviour
- Paired t-test for statistical significance

---

## 📈 Key Results
- Simulated Annealing achieved better solution quality and faster runtime.
- Genetic Algorithm provided strong exploration but required higher computation cost.
- A paired t-test confirmed statistically significant performance differences.

---

## ✅ Learning Outcomes
- Applied AI search algorithms to a real optimisation problem
- Evaluated scalability and robustness of heuristic approaches
- Performed statistical validation using hypothesis testing
- Gained practical experience in experimental AI evaluation

---

## ⚖️ Ethical and Legal Considerations
- The dataset is synthetic and contains no personal data.
- All code is developed for academic use.
- Generative AI tools were used responsibly for understanding and documentation.

---

## 📚 References
- Alanzi, E., & Menai, M. E. B. (2025). *Solving the Travelling Salesman Problem with Machine Learning*. Artificial Intelligence Review.
- Mamatova, Z., & Abdumajidova, M. (2025). *The Travelling Salesman Problem: Mathematical Modelling and Optimal Solutions*. IJAI.

---

## 👤 Author
Coursework submission for **AI for Search and Optimisation (2025–26)**

