Step-by-Step Analysis
1. Data Cleaning and Preprocessing in Excel
Task: Handling missing data and outliers.
Steps:
Identified missing values using filters and Excel’s ISBLANK function.
Missing values in numeric columns were filled with the average using =AVERAGE() function in Excel.
Outliers were detected by sorting columns (e.g., rating, prep_time) and visually checking for extreme values. No further manual action was taken on outliers in Excel.
2. Exploratory Data Analysis (EDA) in Python
Task: Uncover trends, relationships, and outliers.

Python Libraries: Pandas, Matplotlib, Seaborn

DataFrame: df

Steps:

Loading the Data: The dataset was loaded into a DataFrame for analysis.
Basic Statistics: Summary statistics were generated to understand the data distribution.
Correlation Analysis: The correlation matrix was computed to identify potential relationships between variables like rating and prep_time.
Visualizations:
Scatter Plot (Prep Time vs Rating): This visualization examined the relationship between preparation time and ratings.
Histogram (Rating Distribution): This chart illustrated the distribution of ratings across the dataset.
Bar Chart (Top Ingredients in Highly Rated Recipes): This visualization highlighted which ingredients are commonly found in highly rated recipes.
3. Creative Data Exploration Using Tableau
Task: Visualizing trends and relationships in an interactive, storytelling format.
Steps:
Importing Data: The cleaned dataset (epi_r.csv) was imported into Tableau.

Visualizations:

Box Plot for Recipe Ratings by Cuisine Type: Showed the spread and variability in ratings across different cuisines.
Heat Map to analyze the impact of ingredients on ratings: Helped identify high-performing ingredients.
Scatter Plot Matrix for Prep Time vs Rating vs Calories: Used to identify patterns and outliers in recipes based on their prep time, calorie content, and user ratings.
Interactive Dashboard: A dashboard was created combining all three visualizations, allowing for user exploration of key insights like ingredient impact, preparation time sweet spots, and user preferences by cuisine type.

Key Insights
Common Ingredients in Highly Rated Recipes:

Ingredients like garlic, butter, and olive oil were frequently present in highly rated recipes, showing user preference for these elements.
Prep Time vs Recipe Rating:

There was no strong linear correlation between preparation time and rating. However, a trend showed that recipes with a moderate prep time (20-40 minutes) tended to have higher ratings.
User Experience Improvement:

The analysis suggests that enhancing recipes with highly rated ingredients and targeting users with recipes within the optimal prep time range could improve user satisfaction on a recipe platform.
Conclusion
The exploratory analysis provided insights that could drive business decisions, such as optimizing recipe recommendations, enhancing user satisfaction, and improving content based on popular ingredients and prep time preferences. The use of both Python and Tableau allowed for a comprehensive analysis, from basic data cleaning to advanced interactive visualizations.
