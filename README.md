# APPLIED_DATA_SCIENCE_CAPSTONE
 Assuming the role of a Data Scientist working for a startup intending to compete with SpaceX, and in the process, I am  following the Data Science methodology involving data collection, data wrangling, exploratory data analysis, data visualization, model development, model evaluation, and reporting my results to stakeholders.  
# process involved
## collecting the data :
Official Sources: Visit official SpaceX websites or space agencies' databases that provide information on past launches. SpaceX's own website often provides detailed information on their launches.

APIs: Check if there are any APIs available that provide access to SpaceX launch data. Some space-related APIs or general data APIs may offer endpoints for retrieving information about SpaceX launches.

Web Scraping: If there are no APIs available, you can scrape data from websites that publish information about SpaceX launches. Be sure to review the website's terms of service and respect any rate limits or restrictions they have in place.

Public Datasets: Look for public datasets available on platforms like Kaggle, GitHub, or government databases that include SpaceX launch data. These datasets may already be cleaned and formatted for analysis.

Manual Entry: If necessary, you could manually enter data from reliable sources into a spreadsheet or database for use in your dashboard.

## Data wrangling :
Data wrangling is the process of cleaning, transforming, and enriching raw data to make it suitable for analysis. It involves tasks such as handling missing values, correcting data types, performing feature engineering, and integrating data from multiple sources. Data wrangling is a critical step in the data analysis pipeline, as it ensures that the data is accurate, consistent, and well-structured for further analysis and visualization.
## SQL analysis :
Setting up your database: Install and configure the RDBMS of your choice. Create a new database or use an existing one to store your data.

Importing your data: Load your SpaceX launch data into the database. You can do this using SQL INSERT statements, or by importing data from a CSV file using tools provided by your RDBMS.

Writing SQL queries: Use SQL queries to analyze your data. Here are some examples of SQL 
## (EDA) using pandas and matplotlib 
Importing libraries: Import the necessary libraries, including pandas for data manipulation and matplotlib for data visualization.

Loading your data: Load your SpaceX launch data into a pandas DataFrame.

Exploring the data: Use pandas to explore the structure and content of your dataset. Some common exploration tasks include:

Viewing the first few rows of the DataFrame: df.head()
Checking the data types of each column: df.dtypes
Summarizing numerical columns: df.describe()
Checking for missing values: df.isnull().sum()
Visualizing the data: Use matplotlib to create visualizations that help you understand the distribution of variables, relationships between variables, and any patterns or trends in the data. Some common visualization tasks include:

Histograms: plt.hist()
Scatter plots: plt.scatter()
Box plots: plt.boxplot()
Bar plots: plt.bar()
Iterating and refining: Iterate on your analysis by exploring different variables, creating additional visualizations, and refining your understanding of the data.

## Analytics and Dashboard :

Create analytics and visualizations using pandas and Plotly, then design an interactive dashboard with Dash, allowing users to explore SpaceX launch data dynamically.

## predictive analysis : 
Perform predictive analysis by applying machine learning algorithms to historical SpaceX launch data, using features such as launch site, payload mass, and booster version to predict launch success or failure, and integrate the predictive model into the dashboard for real-time launch outcome predictions.
## Present the findings :
Present the findings of the predictive analysis by showcasing the accuracy metrics (e.g., accuracy score, confusion matrix), highlighting important features influencing launch success, and providing insights into the model's performance and limitations. Display the results visually in the dashboard, alongside explanations and interpretations for stakeholders to understand and make informed decisions.
