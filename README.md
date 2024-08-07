### Project Title: Data Analysis and visualisation with MS Excel

#### Overview
This project involves the analysis of a bike buyer dataset using Excel, with the goal of extracting meaningful insights and presenting them in an interactive dashboard. The dataset includes various attributes such as gender, marital status, income, age, and whether a bike was purchased. The project demonstrates a thorough process of data cleaning, transformation, analysis, and visualisation.

#### Dataset Description
The dataset contains the following columns:
- **ID:** Unique identifier for each record.
- **Marital Status:** Marital status of the buyer (M for Married, S for Single).
- **Gender:** Gender of the buyer (M for Male, F for Female).
- **Income:** Income of the buyer in USD.
- **Children:** Number of children.
- **Education:** Education level.
- **Occupation:** Job role of the buyer.
- **Home Owner:** Whether the buyer owns a home (Yes or No).
- **Cars:** Number of cars owned.
- **Commute Distance:** Distance the buyer commutes in miles.
- **Region:** Geographic region of the buyer.
- **Age:** Age of the buyer.
- **Purchased Bike:** Whether the buyer purchased a bike (Yes or No).

#### Project Steps

1. **Data Cleaning and Transformation:**
   - **Duplicate Removal:** Checked for and removed duplicate entries to ensure data integrity.
   - **Standardisation:** Used Find and Replace to standardise values, such as converting marital status from 'M' and 'S' to 'Married' and 'Single'.
   - **Age Brackets:** Created a new column to categorise age into brackets (Young, Middle Aged, Old) using a nested IF formula.
   - **Currency Formatting:** Changed the income column format to currency for better readability.
   - **Data Validation:** Applied filters to identify and correct any inconsistencies or errors in the dataset.

2. **Pivot Tables Creation:**
   - **Gender vs. Bike Purchases:** Created a pivot table to analyse the relationship between gender and bike purchases, displaying the average income of each group.
   - **Commute Distance vs. Bike Purchases:** Analysed how commute distance influences bike purchasing decisions.
   - **Age Brackets vs. Bike Purchases:** Examined bike purchases across different age brackets.

3. **Data Visualisation:**
   - **Clustered Column Chart:** Visualised the relationship between gender and bike purchases, along with average income.
   - **Line Charts:** Created line charts to show trends in bike purchases based on commute distance and age brackets.
   - **Dashboard Assembly:** Combined all visualisations into a single dashboard, using Excel’s formatting tools to create a clean and organised presentation.

4. **Interactive Dashboard with Slicers:**
   - Added slicers to allow users to filter the data by marital status, enabling dynamic interaction with the dashboard.
   - Linked the slicers to all pivot tables to ensure consistent filtering across all visualisations.

#### Key Features
- **Data Cleaning:** Ensured high data quality through comprehensive cleaning and standardisation processes.
- **Descriptive Analysis:** Provided insights into key trends such as the impact of gender, commute distance, and age on bike purchasing decisions.
- **Interactive Dashboard:** Created an interactive dashboard that allows users to explore data through dynamic filtering with slicers.

#### How to Use
- Download the `.xlsx` file and open it in Excel.
- Explore the "Dashboard" tab to interact with the visualisations.
- Use the slicers to filter data by marital status and observe how the visualisations update dynamically.
- Review the "Pivot Table" tab to understand the underlying data summaries.

This project is an excellent example of how Excel can be used to transform raw data into actionable insights, combining data cleaning, statistical analysis, and interactive visualisation.
