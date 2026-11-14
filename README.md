# Innomatics_Research_Labs_Coaching_Web_Scraping

# 📚 Books Market Analysis Using Web Scraping

## 📌 Project Overview

This project focuses on collecting, cleaning, analyzing, and visualizing book-related data from [Books to Scrape](https://books.toscrape.com/), a practice website designed for web scraping.

Using Python and its data analysis libraries, the project extracts book information, performs data preprocessing, creates meaningful features, and conducts Exploratory Data Analysis (EDA) to identify patterns and insights.

## 🎯 Project Objectives

- Extract book information from a website using web scraping.
- Understand and structure the collected data.
- Clean and preprocess raw data.
- Perform feature engineering.
- Conduct Exploratory Data Analysis.
- Create meaningful data visualizations.
- Answer business-related questions using the collected data.

## 🛠️ Technologies & Libraries Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Requests | Sending HTTP requests |
| BeautifulSoup | Extracting website data |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical operations |
| Regex | Text cleaning and pattern matching |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualizations |
| Jupyter Notebook | Development environment |

## 🌐 Data Source

**Website:** [Books to Scrape](https://books.toscrape.com/)

The project collects information from the website's book catalogue.

### Dataset Attributes

- **Title:** Name of the book.
- **Price:** Listed book price.
- **Availability:** Stock availability information.
- **Rating:** Book rating.
- **Product URL:** Link to the individual book page.

The original project collected 1,000 book records across 50 catalogue pages.

## 🔄 Project Workflow

1. **Website Inspection** – Understand the website structure and HTML elements.
2. **Web Scraping** – Extract book information using Requests and BeautifulSoup.
3. **Data Collection** – Store the extracted information in a structured DataFrame.
4. **Data Understanding** – Inspect the dataset using shape, columns, data types, and summary statistics.
5. **Data Cleaning** – Handle missing values, remove unwanted characters, and convert data types.
6. **Feature Engineering** – Create additional features such as price category, rating category, availability flag, and title length.
7. **Exploratory Data Analysis** – Analyze price, ratings, and other book attributes.
8. **Data Visualization** – Generate charts to understand distributions and relationships.
9. **Business Analysis** – Answer business questions using the analyzed data.
10. **Insights & Recommendations** – Summarize findings and identify useful observations.

## 📊 Key Analysis Performed

- Distribution of book prices.
- Distribution of book ratings.
- Comparison of prices across rating categories.
- Identification of the cheapest and most expensive books.
- Analysis of price categories.
- Analysis of highly rated books.
- Relationship between book prices and ratings.
- Comparison of average ratings across price categories.

## 📈 Visualizations

The project includes nine visualizations to explore the collected dataset and communicate the findings.

These visualizations help understand:
- Price distribution.
- Rating distribution.
- Category-wise comparisons.
- Relationships between numerical features.
- Overall patterns in the book catalogue.

## 💡 Key Learnings

Through this project, I gained practical experience in:

- Web scraping using Python.
- HTML parsing with BeautifulSoup.
- Extracting structured information from websites.
- Data cleaning and preprocessing.
- Feature engineering.
- Exploratory Data Analysis.
- Data visualization.
- Answering business questions using data.

## 📁 Project Structure

```text
Books-Market-Analysis/
│
├── Books_Market_Analysis.ipynb
│
├── scraped_books.csv
│
├── cleaned_books.csv
│
├── visualizations/
│   ├── visualization_1.png
│   ├── visualization_2.png
│   └── ...
│
└── README.md
```

*Note: Update the filenames and visualization names to match the files in your repository.*

## ▶️ How to Run the Project

**Step 1:** Clone the repository.

```bash
git clone <your-repository-url>
```

**Step 2:** Navigate to the project folder.

```bash
cd Books-Market-Analysis
```

**Step 3:** Install the required libraries.

```bash
pip install requests beautifulsoup4 pandas numpy matplotlib seaborn openpyxl
```

**Step 4:** Launch Jupyter Notebook.

```bash
jupyter notebook
```

**Step 5:** Open `Books_Market_Analysis.ipynb` and execute the notebook cells sequentially.

## ⚠️ Limitations

- The analysis is based on the information available on the source website at the time of scraping.
- Book prices and availability may change.
- The dataset does not contain actual sales, revenue, or customer-demand information.
- The findings describe the collected catalogue and should not be treated as conclusions about the entire book market.

## 👨‍💻 Author

**Project:** Books Market Analysis Using Web Scraping

**Domain:** Python | Web Scraping | Data Analytics

## ⭐ Acknowledgement

Thanks to [Books to Scrape](https://books.toscrape.com/) for providing a practice website for learning and implementing web scraping techniques.

---

If you find this project useful, consider giving the repository a ⭐!
