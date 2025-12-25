# IMDB Movies Exploratory Data Analysis (EDA)

## Project Introduction
This project performs a complete **Exploratory Data Analysis (EDA)** on the **IMDB Top Movies dataset** to uncover meaningful patterns and insights related to movie ratings, votes, genres, and release trends.

The objective is to demonstrate **core data analysis skills** such as data cleaning, preprocessing, visualization, and interpretation using Python and popular data science libraries.

This project is suitable for **academic submission, beginner data analysis practice, and GitHub portfolio showcase**.

---

## Project Objectives
- Load and understand a real-world dataset  
- Perform data preprocessing and cleaning  
- Conduct basic exploratory data analysis (EDA)  
- Visualize trends and relationships in the data  
- Summarize key insights clearly and concisely  

---

## Dataset Information
- **Dataset Name:** IMDB Top Movies Dataset  
- **File Used:** `imdb_movies.csv`  
- **Source:** IMDB (via Kaggle)  

### Key Columns
- `Series_Title` – Movie title  
- `Released_Year` – Year of release  
- `Genre` – Movie genres  
- `IMDB_Rating` – IMDB rating score  
- `No_of_Votes` – Number of user votes  
- `Runtime` – Duration of the movie  
- `Director`, `Star1–Star4` – Cast and crew details  

---

## Tools & Technologies Used
- Python 3.11  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  
- VS Code  

---

## Project Structure

```
IMDB-Movies-EDA/
│
├── data/
│ └── imdb_movies.csv
│
├── notebooks/
│ └── imdb_eda.ipynb
│
├── reports/
│ └── summary.md
│
├── requirements.txt
└── README.md
```

---

## Data Preprocessing
- Converted numerical columns (`Released_Year`, `IMDB_Rating`, `No_of_Votes`) to proper data types  
- Removed rows with missing values in critical columns  
- Removed duplicate records  
- Cleaned string-based numeric fields where required  

---

## Exploratory Data Analysis (EDA)
- Number of movies released per year  
- Distribution of IMDB ratings  
- Relationship between number of votes and ratings  
- Identification of top-rated movies  
- Genre-wise movie distribution  

Visualizations were created using Matplotlib and Seaborn.

---

## Key Insights
- Most IMDB top movies have ratings between **7 and 8**  
- Movie releases increased significantly after the year **2000**  
- Movies with higher vote counts generally have higher ratings  
- **Drama** is the most dominant genre among top-rated movies  

---

## How to Run the Project

```bash
pip install -r requirements.txt
jupyter notebook notebooks/imdb_eda.ipynb
```
Run all notebook cells sequentially.

---

## Notes

- The notebook is code-only by design
- All explanations and documentation are provided in this README
- This structure follows professional and industry-style project organization

---

## Conclusion
This project demonstrates a structured approach to exploratory data analysis using a real-world dataset. The insights obtained highlight audience preferences and trends in highly rated movies, while showcasing fundamental data analysis and visualization skills.

---

## License
This project is created **strictly for educational and learning purposes**.  
It is intended for academic use, practice, and personal learning, with no commercial intent.

By Jairaj R.
