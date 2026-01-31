## REPOSITORY OVERVIEW ##
Multiple datasets from different formats (CSV, JSON, SQL) are combined into a single, clean dataset and analyzed using Python and Pandas.

## DATASET PROVIDED ##
orders.csv---CSV	(Transactional order data)
users.json---JSON	(User master data)
restaurants.sql---SQL	(Restaurant master data)

## DATA INTEGRATION ##
orders.user_id → users.user_id (LEFT JOIN)
orders.restaurant_id → restaurants.restaurant_id (LEFT JOIN)

## TECH STACK ##
-Python
-Pandas
-SQLite
-Jupyter Notebook (VS Code)

## ANALYSIS ##
-Revenue and order trends
-City-wise and cuisine-wise performance
-Gold vs Regular membership impact
-Rating and seasonal analysis

## HOW TO RUN THE JUPYTER NOTEBOOK --> ##
Open 1st_Quest.ipynb and run all cells sequentially

## OUTCOMES: ##
Working with multiple data formats in Python
Performing joins using Pandas
Data cleaning and preprocessing
Analytical thinking using real-world datasets
Writing clean, well-documented notebooks
