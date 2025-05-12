Data Cleaning & Preprocessing


---

## 🔧 Steps Performed

1. **Loaded the Dataset**  
   - Used Pandas to load the Netflix CSV file.

2. **Explored the Data**  
   - Viewed column types, missing values, and basic stats using `df.info()` and `df.isnull().sum()`.

3. **Handled Missing Values**  
   - Filled missing values with "Unknown"
   - Dropped rows if too many null 

4. **Visualize the data** 
    - used matplot and seaborn to display some insights such as
    - Releases by Year
    - Distribution of ratings
    - Top 10 generes in Netflix

7. **Saved the Cleaned Dataset**  
   - Exported final dataset to `netflix_cleaned.csv`.

---