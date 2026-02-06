# Netflix Data Cleaning Project

## 📌 Objective
To clean and preprocess the Netflix Movies & TV Shows dataset using Pandas.

---

## 📊 Dataset
Netflix Movies and TV Shows dataset containing information about:
- Type (Movie / TV Show)
- Director
- Cast
- Country
- Release Year
- Rating
- Date Added
- Duration

---

## 🧹 Data Cleaning Steps

1. Identified missing values
2. Filled categorical null values with "Unknown"
3. Replaced missing ratings using mode
4. Removed duplicate records
5. Converted `date_added` to datetime format
6. Extracted `year_added` and `month_added`
7. Standardized text columns

---

## 📈 Visualization

Movies vs TV Shows distribution chart saved inside `images/` folder.

---

## 🛠 Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📁 Output

- Cleaned dataset: `cleaned_netflix.csv`
- Visualization: `images/movies_vs_tvshows.png`
