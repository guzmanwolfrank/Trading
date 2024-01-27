# Pivot Point Calculator 
by Wolfrank Guzman 

 # 

 Github: @guzmanwolfrank




## Project Overview 
 
The prime objective of this project is to make a tool useful to NQ 100 Emini Futures traders.  This tool helps calculate pivot points for the NQ 100 Emini contract. 
A seaborn output chart containing prices and pivot levels is also produced.  



### To view the project's Jupyter notebook, click [here](#)

### To view the project's Tableau Dashboard, click [here](#)

## Data Description

This Python script utilizes the yfinance library to fetch historical stock market data for a specified ticker over the last 30 days. The code focuses on the E-mini Nasdaq 100 (NQ) futures contract but can be adapted for other tickers as well.

#### Data Retrieval:

The user is prompted to enter a stock ticker. The default ticker is set to 'NQ=F'.
Historical data for the specified ticker is downloaded from Yahoo Finance for the last 30 days with daily intervals.

#
#### Pivot Points Calculation:

High, low, close, and open prices are extracted from the downloaded data and rounded to two decimal places.
Pivot points, support levels (S1, S2, S3), and resistance levels (R1, R2, R3) are calculated based on traditional pivot point analysis.
Data Presentation:

The calculated pivot points and relevant prices are organized into a Pandas DataFrame named pivot_data.
The last row of this DataFrame (excluding the most recent data) is extracted and printed for informational purposes.

#
#### Visualization:

The script uses Seaborn and Matplotlib to create a line plot depicting the closing prices along with the calculated pivot points, support, and resistance levels.
The y-axis labels are rotated by 90 degrees for better readability.
The resulting plot is displayed, providing a visual representation of the stock's price movement and key technical levels.

#

Note:

This script is designed to analyze and visualize the historical price movements of the specified stock, focusing on pivot points and support/resistance levels.
The code can be adapted for other stock tickers by modifying the initial user input.
Additional customization, such as choosing a different ticker or adjusting the date range, can be easily implemented based on specific requirements.










## Tools and Technology

1. **yfinance:**
   - **Description:** A Python library for accessing financial data from Yahoo Finance.
   - **Usage:** Used to download historical stock market data for analysis and visualization.

2. **Pandas:**
   - **Description:** A powerful data manipulation and analysis library in Python.
   - **Usage:** Utilized to structure and manipulate the downloaded financial data efficiently.

3. **Seaborn and Matplotlib:**
   - **Description:** Data visualization libraries in Python.
   - **Usage:** Used for creating line plots and heatmaps to visually represent stock price movements and technical levels.

## Technology Stack

- **Python:**
  - **Description:** A versatile and widely-used programming language chosen for its readability and ease of use.

- **Jupyter Notebooks (Optional):**
  - **Description:** Can be used for interactive code execution and experimentation.

## Version Control

- **Git:**
  - **Description:** A distributed version control system for tracking changes in the codebase.

## Project Structure

- **README:**
  - **Description:** This document provides an overview of the project, its purpose, and instructions for running and understanding the code.

- **Python Script:**
  - **Description:** The main script written in Python that fetches financial data, calculates pivot points, and visualizes the historical stock price movements.

## Dependencies

- Ensure that the required Python libraries are installed. You can install them using the following command:

```bash
pip install yfinance pandas seaborn matplotlib


## Getting Started
Clone the Repository:

bash
Copy code
git clone https://github.com/your_username/your_project.git
Install Dependencies:

bash
Copy code
pip install -r requirements.txt
Run the Script:

bash
Copy code
python financial_analysis_script.py
Contributing
Contributions and improvements are welcome! Feel free to open issues or submit pull requests.
License
This project is licensed under the MIT License. Feel free to use, modify, and distribute the code.


# Links

# Project Objectives 

# Project Deliverables 

# Goals

# Initial Questions 

# Data Dictionary

# Exploring the Data

# Visualizations 

# Findings 

# Conclusion

# Tech Stack 

# Badges