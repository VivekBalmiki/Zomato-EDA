# 🍽️ Zomato Restaurant Data Analysis - Unveiling Culinary Insights

This project explores the Zomato restaurant dataset to extract valuable insights and patterns through Exploratory Data Analysis (EDA). We aim to understand restaurant distribution, rating trends, cuisine preferences, and more.

## 🚀 Project Overview

-   **Objective:** To perform EDA on the Zomato dataset to gain a deeper understanding of restaurant data and trends.
-   **Tools:** Python (Pandas, NumPy, Seaborn, Matplotlib), Jupyter Notebook.
-   **Dataset:** [Link to the dataset source, if available] (e.g., Kaggle, UCI Machine Learning Repository)

## 📂 Dataset Overview

The dataset provides comprehensive information about restaurants across various countries. Key features include:

-   **Restaurant ID:** Unique identifier for each restaurant.
-   **Restaurant Name:** Name of the restaurant.
-   **Country Code:** Numerical code representing the country.
-   **City:** Location of the restaurant.
-   **Address:** Detailed address.
-   **Locality & Locality Verbose:** Specific region of the city.
-   **Longitude & Latitude:** Geographical coordinates.
-   **Cuisines:** Type of cuisines served.
-   **Average Cost for Two:** Estimated cost for two people.
-   **Currency:** Currency used for transactions.
-   **Has Table Booking:** Availability of table reservations.
-   **Has Online Delivery:** Whether the restaurant offers online delivery.
-   **Is Delivering Now:** Real-time delivery availability.
-   **Switch to Order Menu:** Whether the restaurant has a dedicated order menu.
-   **Price Range:** Price category.
-   **Aggregate Rating:** Overall rating based on user reviews.
-   **Rating Color & Rating Text:** Visual and text-based rating representation.
-   **Votes:** Number of votes received.

## 🛠️ Analysis Performed

### ✅ Handled Missing Values

We began by identifying and addressing missing values in the dataset. Techniques such as imputation or removal were applied to ensure data integrity for subsequent analysis.

### ✅ Explored Numerical Variables

Numerical features were analyzed to understand their distributions, central tendencies (mean, median), and dispersion (standard deviation). Outliers were identified and treated to prevent skewing the analysis.

### ✅ Explored Categorical Variables

Categorical variables were examined to determine the frequency of unique values and their relationships with other variables. This provided insights into restaurant locations, cuisines, and service offerings.

### ✅ Found Relationships Between Features

Correlation analysis and other statistical methods were used to identify relationships and dependencies between features. This helped uncover patterns and potential predictive power.

## 📊 Key Findings & Insights

-   **Geographical Distribution:** Zomato has the most extensive records from **India**, followed by the **USA** and the **UK**, indicating their strong market presence.
-   **Rating Trends:**
    -   **4.5 - 4.9:** Excellent
    -   **4.0 - 4.4:** Very Good
    -   **3.5 - 3.9:** Good
    -   **3.0 - 3.4:** Average
    -   **2.5 - 2.9:** Below Average
    -   **2.0 - 2.4:** Poor
-   **Online Delivery:** Online delivery availability varies significantly by country, suggesting different market adoption rates.
-   **Delhi Transactions:** Delhi has the highest number of transactions, highlighting its vibrant food scene.

## ❓ Specific Questions Addressed

1.  **High count of unrated restaurants:** We investigated the prevalence of restaurants with zero ratings and explored potential reasons (e.g., new establishments, data collection issues).
2.  **Concentration of ratings between 2.5 and 3.4:** Analysis revealed that a significant portion of ratings falls within this range, indicating a need for strategies to improve average ratings.
3.  **Countries with zero ratings:** Identified countries with restaurants having no ratings and explored potential factors contributing to this.
4.  **Variability of online delivery:** Analyzed the distribution of online delivery availability across countries and identified key differences.
5.  **Delhi's transaction dominance:** Examined the data to confirm and understand the reasons behind Delhi's high transaction volume.

## ▶️️ How to Run the Analysis

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/VivekBalmiki/Zomato-EDA.git
    cd Zomato-EDA
    ```
2.  **Install Dependencies:**
    ```bash
    pip install pandas numpy seaborn matplotlib jupyter
    ```
3.  **Open Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
4.  **Run the Notebook:** Open and execute the `Zomato_EDA.ipynb` notebook.

## 📊 Visualization & Future Work

-   **Top 10 Cuisines Analysis:** Conduct in-depth analysis on the top 10 most popular cuisines, including their rating distributions and geographical spread.
-   **Advanced Visualizations:** Develop interactive and insightful visualizations using tools like Plotly or Dash to provide a more dynamic understanding of the data.
-   **Predictive Modeling:** Explore the possibility of building predictive models to forecast restaurant ratings or transaction volumes.
-   **Geographical Analysis:** Enhance the geographical analysis by creating maps and visualizations to show restaurant distribution and rating patterns across different regions.

## 🤝 Contributions & Feedback

Contributions and feedback are highly encouraged! If you have suggestions for improvements or would like to contribute to the project, please feel free to submit a pull request or open an issue.

---

🚀 Let's explore the world of restaurants with data! 🍽️
