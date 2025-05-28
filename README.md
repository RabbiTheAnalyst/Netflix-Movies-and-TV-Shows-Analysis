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
   ![Distribution of Content Types](https://github.com/RabbiTheAnalyst/Netflix-Movies-and-TV-Shows-Analysis/blob/main/Distribution%20of%20Content%20Types.png)  
   

2. **Top 10 Primary Genres:**  
   - "Dramas" and "Comedies" are among the most prevalent genres.  
   ![Top 10 Primary Genres](https://github.com/RabbiTheAnalyst/Netflix-Movies-and-TV-Shows-Analysis/blob/main/Top%2010%20Primary%20Genres.png)  


3. **Top 10 Primary Countries (Content Production):**  
   - The United States and India are leading content producers.  
   ![Top 10 Primary Countries](https://github.com/RabbiTheAnalyst/Netflix-Movies-and-TV-Shows-Analysis/blob/main/Top%2010%20Primary%20Country.png)  
  

4. **Number of Content Added to Netflix Per Year:**  
  ![Number of Content Added to Netflix Per Year](https://github.com/RabbiTheAnalyst/Netflix-Movies-and-TV-Shows-Analysis/blob/main/Number%20of%20Content%20Added%20to%20Netflic%20Per%20Year.png)

---

✅ **Outcome:** The project delivered a data-driven understanding of Netflix’s content catalog, backed by clean visuals and statistical insights.  

### 📈 Power BI Dashboard Showcase

An interactive dashboard was created in Power BI to provide a comprehensive overview of the Netflix content library. The dashboard allows users to dynamically filter and explore the data.

#### 🔍 Dashboard Highlights:
- **KPIs:** Total Titles, Average Movie Duration, Content by Country, etc.  
- **Genre & Ratings:** Visual breakdown of genres, ratings, and content types.  
- **Geographical Insights:** Country-wise distribution of Netflix content.  
- **Time Trends:** Year-wise trend analysis of content addition.

<br>

![Netflix Power BI Dashboard](https://github.com/RabbiTheAnalyst/Netflix-Movies-and-TV-Shows-Analysis/blob/main/Rabbi_Netflix_Dashboard.png)  

## 🔮 Future Scope

- Perform sentiment analysis on movie/show descriptions.  
- Analyze the relationship between cast/directors and content ratings/popularity.  
- Explore trends in content duration over the years.  
- Develop a recommendation system based on user preferences (more advanced).

--- 

## 👨‍💻 Author Contact

<div align="left"> <table> <tr> <td align="center" style="padding: 10px;"> <a href="mailto:rabbi.stat.iu@gmail.com" target="_blank"> <img src="https://img.icons8.com/color/48/gmail--v1.png" alt="Email" width="40" /> <br><sub><b>Email</b></sub> </a> </td> <td align="center" style="padding: 10px;"> <a href="https://www.linkedin.com/in/rabbi-the-analyst" target="_blank"> <img src="https://img.icons8.com/color/48/linkedin.png" alt="LinkedIn" width="40" /> <br><sub><b>LinkedIn</b></sub> </a> </td> <td align="center" style="padding: 10px;"> <a href="https://github.com/RabbiTheAnalyst" target="_blank"> <img src="https://img.icons8.com/fluent/48/github.png" alt="GitHub" width="40" /> <br><sub><b>GitHub</b></sub> </a> </td> <td align="center" style="padding: 10px;"> <a href="https://wa.me/8801740083864" target="_blank"> <img src="https://img.icons8.com/color/48/whatsapp--v1.png" alt="WhatsApp" width="40" /> <br><sub><b>WhatsApp</b></sub> </a> </td> <td align="center" style="padding: 10px;"> <a href="https://t.me/Rabbi_Bhai" target="_blank"> <img src="https://img.icons8.com/color/48/telegram-app--v1.png" alt="Telegram" width="40" /> <br><sub><b>Telegram</b></sub> </a> </td> </tr> </table> </div>

<div align="left" style="margin-top: 30px;">
💡 If you found this project useful, feel free to give it a ⭐ star and follow me for more data-driven projects.

📢 Your support motivates me to keep learning and sharing, In Sha Allah!



