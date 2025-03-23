# Chocolate_flavanol_heavymetals
Dark Chocolate Health Assessment - Bryan Johnson YouTube Video data

📌 Project Overview

This project analyzes the relationship between flavanol content, heavy metal contamination, and the overall score of different chocolate brands. The dataset includes information on:

Flavanols (mg): Antioxidant compounds beneficial for health

Heavy Metals (µg): Contaminants such as lead and cadmium

Score: A rating for chocolate quality

Calories per 100g: Energy content per brand

Through visualizations and correlation analysis, we aim to understand:

How heavy metal levels impact the chocolate score

Whether flavanol content boosts the score

The relationship between flavanol levels and heavy metals

🛠️ Technologies Used

Python

Pandas for data manipulation

Matplotlib & Seaborn for data visualization

📊 Key Visualizations

🔹 Correlation Analysis

A heatmap shows the correlation between flavanols, heavy metals, and score

Finding: Heavy metals have a strong negative correlation (-0.79) with the score, meaning higher contamination leads to lower ratings

🔹 Scatter Plots

Flavanols vs. Heavy Metals: Identifies if higher flavanol chocolates have more contaminants

Annotated Scatter Plot: Highlights chocolates exceeding 5µg of heavy metals

Regression Trendline: Shows the overall trend

🔹 Bar Plot for Calories

Displays the calorie content per 100g for different chocolate brands

🚀 How to Run the Code

Prerequisites

Ensure you have Python installed along with the required libraries:

pip install pandas matplotlib seaborn openpyxl

Running the Script

Place your Excel file (Book1.xlsx) in the project directory

Run the Python script:

python analysis.py

📌 Next Steps

Use multiple regression to quantify how much score is impacted by flavanols vs. heavy metals

Explore the flavanol-to-heavy metal ratio as a better indicator of quality

Expand the dataset for more brands

📢 Author: Umair Zia 📅 Last Updated: 22-03-2025
