# Mobile Phones Data Analysis Using Python Web Scraping
This project involves extracting, cleaning, and analyzing mobile phone data from Flipkart using Python. The goal was to gather insights into mobile phone specifications, prices, and user reviews, providing valuable insights for data-driven decision-making.

## Project Workflow

### 1. **Web Scraping**
- **Objective**: Extract mobile phone data, including specifications, prices, ratings, and reviews, directly from Flipkart.
- **Tools and Libraries**: 
  - `BeautifulSoup`: To parse HTML and extract relevant elements.
  - `Requests`: To send HTTP requests and fetch web pages.
  - `Pandas`: For data handling and structuring.
  - **Keywords**: HTML parsing, CSS selectors, data scraping, dynamic content handling.
- **Process**:
  - Identified Flipkart’s product listing structure and targeted key attributes such as Brand, Color, Version, Price, Ratings, and Reviews.
  - Used Python scripts to automate data extraction across multiple pages.

### 2. **Data Cleaning**
- **Objective**: Prepare raw scraped data for meaningful analysis.
- **Techniques and Tools**:
  - **Regex (Regular Expressions)**: For pattern matching and cleaning inconsistent data.
  - `Pandas`: For handling missing values, renaming columns, and transforming data types.
  - **Steps**:
    - Removed duplicates and irrelevant rows (e.g., ads or sponsored products).
    - Standardized columns like price formats, storage capacities, and star ratings.
    - Handled missing values using imputation or deletion based on relevance.

### 3. **Exploratory Data Analysis (EDA)**
- **Objective**: Derive insights through graphical representation and statistical analysis.
- **Techniques and Analysis**:
  - **Univariate Analysis**: 
    - Explored individual features like price distributions, rating frequencies, and review counts.
    - Graphs Used: Histograms, Boxplots, and Countplots.
  - **Bivariate Analysis**:
    - Investigated relationships between two variables, such as price vs. ratings or storage capacity vs. price.
    - Graphs Used: Scatterplots, Heatmaps, and Bar Charts.
  - **Tools**:
    - `Matplotlib` and `Seaborn`: For creating visually appealing and insightful graphs.
    - Statistical insights were supported by Python libraries like `numpy`.

### 4. **Insights and Findings**
- **Key Insights**:
  - Identified popular mobile brands and their price ranges.
  - Correlated higher ratings with specific storage capacities and versions.
  - Uncovered pricing trends and customer preferences based on review analysis.
- **Value Addition**: Provided a comprehensive analysis of Flipkart’s mobile phone inventory to assist buyers or marketers.

### 5. **Challenges**
- Dynamic content and pagination required effective handling of delays and session management.
- Data cleaning involved extensive regex for unstructured data patterns.
- Filtering meaningful insights from large datasets.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: 
  - Data Scraping: `BeautifulSoup`, `Requests`
  - Data Cleaning: `Pandas`, `Regex`
  - Visualization: `Matplotlib`, `Seaborn`
  - Others: `NumPy` for numerical operations

## Conclusion
This project demonstrates the practical application of Python web scraping, data cleaning, and exploratory data analysis. The insights derived from this dataset provide a strong foundation for making data-driven decisions in e-commerce analytics. 
