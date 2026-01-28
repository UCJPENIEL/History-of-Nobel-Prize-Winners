# 🏆 Nobel Prize Analysis (1901–2023)

## 📌 Project Overview
This project analyzes Nobel Prize data from 1901 to 2023, uncovering key trends in gender, nationality, and category distribution.  
All visuals were built in **Jupyter Notebook** using **Matplotlib** and **Seaborn**.

---

## 🎯 Objectives
- Explore demographic and geographic patterns of laureates.  
- Identify long-term shifts in Nobel recognition.  
- Present findings with clear, professional visualizations.  

---

## 📊 Dataset
- **Source:** Nobel Prize dataset (`nobel.csv`).  
- **Features:** Year, Category, Birth Country, Sex, Motivation, etc.  
- **Derived Columns:**  
  - `decade` → Groups laureates by decade  
  - `is_female` → Gender flag  
  - `is_us_born` → US-born flag  

---

## 🔍 Key Insights
- **Gender gap:** Nobel Prizes remain male-dominated, though female representation is slowly improving.  
- **US dominance:** Since the mid-20th century, US-born laureates have consistently led across categories.  
- **Country diversity:** Physics and Chemistry show concentrated awards, while Peace Prizes have the most diverse set of laureates.  

---

## 📸 Visualizations
*(Export your plots as PNGs, save them in an `/images` folder, and replace the links below.)*

- **Gender Distribution**  
  ![Gender Distribution](images/gender_distribution.png)

- **US-born Laureates by Decade**  
  ![US Born by Decade](images/us_born_by_decade.png)

- **Female Laureates by Category & Decade**  
  ![Female Laureates](images/female_laureates.png)

- **Top Birth Countries**  
  ![Top Countries](images/top_birth_countries.png)

---

## 🖥️ Run Locally
```bash
# Install dependencies
pip install pandas matplotlib seaborn jupyter

# Launch Jupyter Notebook
jupyter notebook Nobel_Analysis.ipynb

---

## 📊 Sample Visualizations  

| Crimes by Hour | Top 5 Areas with Night Crimes | Victim Age Groups |
|----------------|-------------------------------|------------------|
|<img width="1023" height="545" alt="image" src="https://github.com/user-attachments/assets/94e1bb92-034e-4bd9-974e-4fdf3e74404e" />|<img width="704" height="520" alt="image" src="https://github.com/user-attachments/assets/c4855c75-d355-473e-a01a-abddda45988e" />|<img width="713" height="493" alt="image" src="https://github.com/user-attachments/assets/7efd1071-3c6e-42f5-864b-ce05dc6b3a7f" />|

---

## 🚀 How to Run the Project  

1. Clone the repository:  

   ```bash
   git clone https://github.com/YourUsername/lapd-crime-analysis.git
   cd lapd-crime-analysis
