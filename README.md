# GenAI Assignment

This repository contains the solution to a group assignment for the Master in Data Science for Business (DSS), Block 2, Business AI course. The assignment focuses on prompt engineering and the application of generative AI (OpenAI GPT-3.5-turbo) to analyze Amazon product review data.

## Repository Structure

- `GenAi.ipynb`: Jupyter Notebook with the full assignment, including code, analysis, and visualizations.
- `data_amazon.csv`: Dataset of Amazon product reviews used for analysis.
- `Group Assignment Prompt Engineering.pdf`: Assignment instructions and requirements.

## Assignment Overview

The goal of this assignment is to:
- Apply prompt engineering techniques (zero-shot and few-shot) to extract product names from customer reviews using OpenAI's GPT-3.5-turbo.
- Analyze factors influencing sales variations using chain-of-thought prompting.
- Identify the most and least profitable product categories.
- Visualize key insights such as total income by product type, price ranges, average ratings, and product distribution.
- Explore additional business questions, including negative trends in low-rated products and seasonality in sales and color preferences.

## Key Features

- **Prompt Engineering**: Demonstrates both zero-shot and few-shot approaches for extracting structured information from unstructured text.
- **Data Analysis**: Cleans and explores the dataset, calculates profitability, and investigates sales factors.
- **Visualization**: Uses matplotlib to visualize income, price ranges, ratings, and product distribution.
- **Business Insights**: Answers business questions using both data analysis and generative AI for deeper insights.

## How to Use

1. Clone this repository.
2. Open `GenAi.ipynb` in Jupyter or VS Code.
3. Ensure you have the required Python packages installed (`openai`, `pandas`, `fuzzywuzzy`, `matplotlib`).
4. Add your OpenAI API key in the notebook where indicated.
5. Run the notebook cells to reproduce the analysis and visualizations.

## Requirements

- Python 3.8+
- Packages: `openai`, `pandas`, `fuzzywuzzy`, `matplotlib`

## License
This project is for educational purposes only.
