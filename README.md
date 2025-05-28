<div align="center">
  <img src="https://github.com/RabbiTheAnalyst/Netflix-Movies-and-TV-Shows-Analysis/blob/main/netflix-vector-flat-logo-735811696261671nhzlvgcmyf-removebg-preview.png" width="300" alt="Project Logo"/>
  <h1>📺 Netflix Movies and TV Shows Analysis</h1>
  <p>This project aims to analyze the Netflix movies and TV shows dataset to uncover insights about content trends, distribution, and popular genres. The analysis involves data cleaning and preprocessing using Python (Pandas), exploratory data analysis (EDA) with visualizations (Matplotlib & Seaborn), and the creation of an interactive dashboard using Power BI.</p>
</div> 

## 💾 Dataset

The dataset used for this analysis is the **"Netflix Movies and TV Shows"**.
* **Source:** [Netflix Movies and TV Shows DataSet](https://github.com/RabbiTheAnalyst/Netflix-Movies-and-TV-Shows-Analysis/blob/main/Netflix_cleaned_data.csv)


## 🛠️ Tools & Technologies

<table>
  <tr>
    <td align="center" width="150">
      <a href="https://powerbi.microsoft.com/en-us/" target="_blank" rel="noreferrer">
        <img src="https://img.icons8.com/color/48/000000/power-bi.png" alt="Power BI" width="48" height="48"/>
      </a>
      <br>
      <strong>Power BI</strong>
      <br>
      <small>Interactive dashboard</small>
    </td>
    <td align="center" width="150">
      <a href="https://www.python.org/" target="_blank" rel="noreferrer">
        <img src="https://img.icons8.com/color/48/000000/python--v1.png" alt="Python" width="48" height="48"/>
      </a>
      <br>
      <strong>Python</strong>
      <br>
      <small>Data manipulation & EDA</small>
    </td>
    <td align="center" width="150">
      <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ed/Pandas_logo.svg/1200px-Pandas_logo.svg.png" alt="pandas" width="90" height="45"/>
      </a>
      <br>
      <strong>pandas</strong>
      <br>
      <small>Data cleaning & wrangling</small>
    </td>
    <td align="center" width="150">
      <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer">
        <img src="https://seaborn.pydata.org/_static/logo-wide-lightbg.png" alt="seaborn" width="90" height="25" style="margin-top: 10px; margin-bottom: 10px;"/>
      </a>
      <br>
      <strong>seaborn</strong>
      <br>
      <small>Statistical visualization</small>
    </td>
    <td align="center" width="150">
      <a href="https://matplotlib.org/" target="_blank" rel="noreferrer">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/84/Matplotlib_icon.svg/2048px-Matplotlib_icon.svg.png" alt="matplotlib" width="48" height="48"/>
      </a>
      <br>
      <strong>matplotlib</strong>
      <br>
      <small>Data plotting</small>
    </td>
  </tr>
</table>  


---
## ⚙️ Project Workflow

The project followed these key steps:

1. **Data Loading and Initial Inspection:**  
   Loaded the `netflix_titles.csv` dataset and performed initial checks for data structure, missing values, and data types.

2. **Data Cleaning and Preprocessing (Python):**  
   - Handled missing values in `director`, `cast`, and `country` columns by filling them with "Unknown".  
   - Dropped rows with missing values in `date_added`, `rating`, and `duration`.  
   - Converted `date_added` to datetime objects.  
   - Extracted `primary_country`, `primary_genre`, and `year_added` for more focused analysis.  
   - The cleaned dataset was saved as `Netflix_cleaned_data.csv`.

3. **Exploratory Data Analysis (EDA) with Python:**  
   - Analyzed the distribution of content types (Movies vs. TV Shows).  
   - Identified the top 10 primary genres and countries.  
   - Visualized the trend of content added to Netflix per year.

4. **Interactive Dashboard Creation (Power BI):**  
   - Imported the cleaned dataset into Power BI.  
   - Created various visualizations (KPI cards, bar charts, donut chart, area chart, map) to present key insights.  
   - Designed a user-friendly and visually appealing dashboard following Netflix's branding theme.

---

## 📊 Key Insights & Visualizations

### Python EDA Highlights:

Here are some of the key visualizations generated using Python:

1. **Distribution of Content Types:**  
   - A significant portion of the content on Netflix consists of Movies.  
   ![Distribution of Content Types](images/Distribution_of_Content_Types.png)  
   *(Assuming you have this image in an 'images' folder in your repository)*

2. **Top 10 Primary Genres:**  
   - "Dramas" and "Comedies" are among the most prevalent genres.  
   ![Top 10 Primary Genres](images/Top_10_Primary_Genres.png)  
   *(Assuming you have this image in an 'images' folder in your repository)*

3. **Top 10 Primary Countries (Content Production):**  
   - The United States and India are leading content producers.  
   ![Top 10 Primary Countries](images/Top_10_Primary_Country.png)  
   *(Assuming you have this image in an 'images' folder in your repository)*

4. **Number of Content Added to Netflix Per Year:**  
   *(Add corresponding image here if available)*

---

✅ **Outcome:** The project delivered a data-driven understanding of Netflix’s content catalog, backed by clean visuals and statistical insights.


