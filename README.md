Data Science TA Hiring Assignment – Cuvette
This repository contains my submission for the Data Science Teaching Assistant (TA) Hiring Assignment at Cuvette. The purpose of this assignment is to demonstrate my technical knowledge, problem-solving skills, and ability to explain data science concepts clearly.

Sections Covered:
Section 1: Python + Machine Learning(https://github.com/Farhanahoque251/Data-Science-TA-Hiring-Assignment-Cuvette/blob/main/student_pass_prediction.ipynb)

Section 2: SQL(https://docs.google.com/document/d/1q-e2CO9LCxzyOx5260dW4Fjz3afaCqfv3BgkCPV-9-I/edit?tab=t.0)

Section 3: Tableau(https://docs.google.com/document/d/1N9eHHH2qhJ_6hi5H_p6PZx6JbvW_2F-NKV1hP4meB9g/edit?tab=t.0)

Section 4: Excel(https://docs.google.com/spreadsheets/d/17S8HqvlM7_ADAQ0Lv-UO8scpexZpzdIW/edit?usp=sharing&ouid=106564686283972622125&rtpof=true&sd=true)

Section 5: Bonus (Optional)(https://docs.google.com/document/d/1DGmP6E3xX5YGxc60kF2JaGWPaJh-SFaVGulWErKSSXA/edit?usp=sharing)

Section 6: AI Tools & LLMs(https://docs.google.com/document/d/1YZE7fzYWsuvwbREdL3qG2NuILgVHqZBSPgSGyJDk9SE/edit?usp=sharing)

📂 Files Included:
Jupyter notebook (.ipynb) for Python + Machine Learning (Section 1)

SQL query file (.sql) for SQL queries (Section 2)

Tableau Public dashboard link for Tableau visualization (Section 3)

Excel file (.xlsx) for Excel analysis (Section 4)

README.md summarizing all steps and solutions

Screen recording (10-15 minutes, uploaded to Google Drive or YouTube - unlisted)

✅ Section 1: Python + Machine Learning (1.5 hours)
Dataset: Student Performance Dataset (Math & Portuguese)

Tasks:

Cleaned and preprocessed the data

Performed exploratory data analysis (EDA) using visualizations (seaborn, matplotlib)

Built a classification model using Logistic Regression

Evaluated the model using accuracy, confusion matrix, F1-score

Included comments and markdown for clarity

You can find the code for Section 1 :
[_python_ml.ipynb Jupyter notebook.](https://github.com/Farhanahoque251/Data-Science-TA-Hiring-Assignment-Cuvette/blob/main/student_pass_prediction.ipynb)

✅ Section 2: SQL (30–45 mins)
Dataset: Chinook Database (Music Store)

Tasks:

Listed the top 5 customers by total purchase amount

Found the most popular genre in terms of total tracks sold

Retrieved employees who are managers along with their subordinates

Identified most sold album for each artist

Wrote a query to get monthly sales trends in 2013

You can find the SQL queries in the section2_sql.sql file.
https://docs.google.com/document/d/1q-e2CO9LCxzyOx5260dW4Fjz3afaCqfv3BgkCPV-9-I/edit?usp=sharing

1.https://sqliteonline.com/#sqltext=%23url-sqlite%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Flerocha%2Fchinook-database%2Fmaster%2FChinookDatabase%2FDataSources%2FChinook_Sqlite.sqlite%0D%0A%23tab-name%3DChinook_Sqlite.sqlite%0D%0A--%20Query%201%3A%20Top%205%20customers%20by%20total%20purchase%20amount%0ASELECT%20%0A%20%20%20%20c.FirstName%20%7C%7C%20'%20'%20%7C%7C%20c.LastName%20AS%20CustomerName%2C%0A%20%20%20%20SUM(i.Total)%20AS%20TotalPurchase%0AFROM%20%0A%20%20%20%20Customer%20c%0AJOIN%20%0A%20%20%20%20Invoice%20i%20ON%20c.CustomerId%20%3D%20i.CustomerId%0AGROUP%20BY%20%0A%20%20%20%20c.CustomerId%0AORDER%20BY%20%0A%20%20%20%20TotalPurchase%20DESC%0ALIMIT%205%3B%0A%0A


✅ Section 3: Tableau (30 mins)
Dataset: Airbnb Listings in NYC

Tasks:

Created a dashboard to visualize:

Listings count by neighborhood

Price distribution per room type

Availability trends

Added filters for room type and neighborhood

Published the dashboard to Tableau Public for public sharing

Link to Tableau Public Dashboard:
https://public.tableau.com/views/NYCAirbnbDashboard_17443666584060/AirbnbListingsinNYC?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

✅ Section 4: Excel (30 mins)
Dataset: Online Retail Dataset (UCI)

Tasks:

Cleaned the data by removing nulls and duplicates

Created a pivot table to show total sales by country and month

Added formulas to calculate:

Average order value

% contribution of each country to total sales

Highlighted top 5 countries by revenue using conditional formatting

Created a chart to visualize monthly revenue trends

You can find the completed Excel file in section4_excel.xlsx.

✅ Section 5: Bonus (Optional, ~15 mins)
Reflection on Supporting Students & Explaining Complex Topics:

Supporting Students:
As a TA, I would focus on creating a supportive and accessible environment for students. For students struggling with concepts, I would offer additional office hours, provide detailed explanations, and use visual aids to clarify complex topics. I would also encourage students to break down large tasks into smaller milestones to avoid feeling overwhelmed by deadlines.

Explaining Gradient Descent:
To explain Gradient Descent to beginners, I would use a real-world analogy of walking down a hill while blindfolded. The goal is to find the lowest point (minimizing the error). We use the slope (gradient) of the hill to determine our next step. In machine learning, we use gradient descent to minimize the error of a model by adjusting parameters iteratively.

✅ Section 6: AI Tools & LLMs (30 mins)
Option A: Prompt Engineering

Prompt Used:
"Write an Excel formula to calculate average order value using total revenue and number of orders"

AI Response:
=TotalRevenue/NumberOfOrders

Reflection:
The AI provided a correct formula based on the given prompt. I used it directly in my Excel file, but I modified the cell references to match my dataset. The AI did well by providing a quick solution, but I had to make minor adjustments for my specific use case.

🎥 Video Recording (Mandatory)
I have recorded a 10-15 minute video that explains each part of my solution step-by-step, talking through the challenges and how I solved each problem.

Watch the video here

Open the Jupyter notebook for Python + ML (section1_python_ml.ipynb) to run the code.

Open the SQL queries in section2_sql.sql using any SQL IDE.

Download the Excel file (section4_excel.xlsx) and open it in Excel to review the analysis.

Visit the Tableau Public dashboard link to see the visualizations.

Acknowledgments
Dataset Credits:

Student Performance Dataset (Math & Portuguese) from UCI Machine Learning Repository

Chinook Database (Music Store) from the Chinook Project

Airbnb Listings dataset from Kaggle

Online Retail Dataset from UCI Machine Learning Repository

