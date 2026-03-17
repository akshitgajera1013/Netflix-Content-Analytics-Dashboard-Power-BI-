# 🎬 Netflix Content Analytics Dashboard (Power BI)

An interactive **Power BI dashboard** designed to analyze Netflix’s global catalog of movies and TV shows.
This project explores content distribution, ratings, geographic availability, and the balance between movies and TV shows through interactive visualizations.

---

# 📂 Dataset Overview

The dataset contains information about Netflix titles including movies and TV shows available on the platform.

### Key Characteristics

* Total Records: ~9,000 titles
* Content Types: Movies and TV Shows
* Countries Covered: 700+
* Multiple content ratings and genres

### Main Columns

| Column       | Description                                       |
| ------------ | ------------------------------------------------- |
| title        | Name of the Netflix title                         |
| type         | Indicates whether the title is a Movie or TV Show |
| director     | Director of the content                           |
| cast         | Main actors featured                              |
| country      | Country where the content was produced            |
| date_added   | Date the title was added to Netflix               |
| release_year | Original release year of the title                |
| rating       | Content rating (TV-MA, PG-13, etc.)               |
| duration     | Length of movie or number of seasons              |
| listed_in    | Genre or category                                 |
| description  | Short summary of the title                        |

The dataset enables analysis of Netflix’s catalog growth, content distribution by country, and viewer rating trends.

---

# 📊 Dashboard Overview

The report contains **two main analytical pages**.

---

# 📌 Page 1 — Netflix Overview Dashboard

This page provides a **high-level summary of Netflix content**.

### Key Metrics

* Total Titles
* Total Movies
* Total TV Shows
* Total Countries

### Visualizations

* **Total Movies by Country**
  Shows which countries produce the most Netflix movies.

* **Total TV Shows by Country**
  Displays distribution of TV shows globally.

* **Movies vs TV Shows Ratio**
  Compares the proportion of movies and TV shows.

* **Rating Distribution**
  Shows how content is categorized by rating (TV-MA, TV-14, etc.).

### Filters

Interactive slicers allow filtering by:

* Country
* Content Type
* Rating
* Year Added

---

# 🌍 Page 2 — Global Content Insights

This page focuses on **geographical and rating analysis**.

### Visualizations

* **Global Map of Netflix Content**
  Displays distribution of titles across countries.

* **Titles by Country**
  Shows top countries producing Netflix content.

* **Movies vs TV Shows by Country**
  Compares the type of content produced in each country.

* **Rating Distribution**
  Highlights how content ratings are distributed globally.

---

# 🎨 Dashboard Design

The dashboard uses a **Netflix-inspired theme**:

* Dark background
* Netflix red highlight color
* High contrast visuals
* Minimalistic layout for readability

---

# 🛠 Tools & Technologies

* **Power BI**
* **DAX Measures**
* Data Cleaning & Transformation
* Interactive Data Visualization

---

# 📈 Key Insights

Some insights revealed through the dashboard:

* The **United States produces the majority of Netflix content**.
* Movies dominate the platform compared to TV shows.
* **TV-MA and TV-14 ratings** represent the largest share of titles.
* Netflix content is distributed across **hundreds of countries**.

---

# 📷 Dashboard Preview

*(Add screenshots of your dashboard here)*

---

# 📁 Project Structure

```
Netflix-PowerBI-Dashboard
│
├── dataset
│   └── netflix_titles.csv
│
├── dashboard
│   └── netflix_dashboard.pbix
│
├── images
│   └── preview.png
        gloabal_content.png
│
└── README.md
```

---

# 🚀 How to Use

1. Download the `.pbix` file from the repository.
2. Open it using **Power BI Desktop**.
3. Explore the interactive dashboard and apply filters.

---

# 👨‍💻 Author

**Akshit Gajera**

Data Science & Machine Learning Enthusiast
Skilled in Python, Machine Learning, Power BI, and Data Visualization.

---

# ⭐ If you like this project

Give the repository a **star ⭐ on GitHub**.
