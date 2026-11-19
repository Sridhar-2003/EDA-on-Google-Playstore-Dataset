# Google Play Store Exploratory Data Analysis (EDA)

## 📌 Project Overview
An Exploratory Data Analysis of the Google Play Store dataset (`googleplay.csv`). This project focuses on data cleaning, preprocessing, and visualizing metadata from Android applications to uncover what drives app popularity, user ratings, and install numbers.

## 📁 Repository Structure
```text
├── googleplay.csv          # Raw dataset used for the analysis
├── your_notebook.ipynb     # Main Jupyter Notebook containing code, visuals, and insights
└── README.md               # Project documentation
```

## 🗂️ Dataset Overview (`googleplay.csv`)
The dataset is included directly in this repository for immediate reproducibility. Key columns analyzed include:
* **App & Category:** Application name and market genre (e.g., Game, Family, Tools).
* **Rating & Reviews:** Overall user rating (1–5) and total number of user reviews.
* **Size & Installs:** App file size and total download brackets.
* **Type & Price:** Free vs. Paid classification and retail price.
* **Content Rating & Genres:** Target age group and sub-genres.

## 🎯 Key Questions Explored
* Which app categories dominate the Play Store in volume vs. total installs?
* How do app size, pricing (Free vs. Paid), and content rating influence user ratings?
* What data cleaning steps were required (e.g., handling missing values, converting `+` and `M`/`k` strings to numeric formats)?

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## 📊 Key Insights
* *[Replace with your top 3 findings, e.g.:]*
* **Free vs. Paid:** Over 90% of the apps in the dataset are free, accounting for the vast majority of total installs.
* **Top Categories:** *Family* and *Game* hold the highest number of apps, while *Communication* and *Social* lead in average installs per app.
* **Rating Distribution:** App ratings are heavily left-skewed, with the majority clustering between 4.0 and 4.5.

## 🚀 How to Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com
   cd your-repo-name
   ```
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
3. Launch Jupyter Notebook and run `your_notebook.ipynb` (the notebook loads `googleplay.csv` directly from the root folder).
4.
