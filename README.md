---
# 🎥 Movie Recommender System using SVD (Matrix Factorization)

This project implements a **Recommender System** using **Singular Value Decomposition (SVD)**, a popular **matrix factorization** technique in collaborative filtering.  
It is designed to recommend movies to users based on their past ratings and the ratings of other similar users.

---

## 📌 Features
- Implements **Collaborative Filtering** using SVD.
- Learns **latent factors** for users and items.
- Predicts missing ratings in the user-item matrix.
- Recommends top movies for each user.
- Jupyter Notebook for step-by-step implementation.

---

## 🛠️ Technologies Used
- **Python 3**
- **NumPy** – numerical computations
- **Pandas** – data handling
- **Scikit-learn** – train-test splitting, evaluation
- **Surprise (optional)** – recommendation algorithms
- **Matplotlib / Seaborn** – visualization

---

## 📂 Project Structure
```

├── SVD\_Recommender\_System.ipynb   # Main Jupyter Notebook
├── README.md                      # Project Documentation
└── data/                          # (Optional) Dataset directory

````

---

## 📊 Dataset
This project works with any **user-item rating matrix**.  
For demonstration, you can use:
- **MovieLens Dataset** (commonly used in recommender systems research)  
  👉 [MovieLens 100K Dataset](https://grouplens.org/datasets/movielens/100k/)  

Make sure to place the dataset inside the `data/` folder or update the notebook path accordingly.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/pranavpatil2316/SVD-Recommender-System.git
   cd SVD-Recommender-System
   
2. Install dependencies:

   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn scikit-surprise


3. Open Jupyter Notebook:

   ```bash
   jupyter notebook SVD_Recommender_System.ipynb
  

4. Run all cells step by step.

---

## 📈 Evaluation

* Uses **RMSE (Root Mean Square Error)** for rating prediction accuracy.
* Provides **Top-N movie recommendations** for each user.

---

## 📌 Future Improvements

* Implement **Hybrid Recommender System** (Content + Collaborative).
* Add **Deep Learning-based** recommendation (e.g., Autoencoders, Neural CF).
* Deploy model as a **Flask/Django Web App**.

---
