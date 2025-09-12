# Summary-Statistics
Basic Data Analysis App (Streamlit)

An interactive Streamlit app for performing basic data analysis on CSV files. The app allows users to upload their dataset, explore summary statistics, analyze individual columns, and visualize data distributions easily.

## Features

Upload any CSV file for analysis

Preview the dataset (first 5 rows)

Generate summary statistics with Pandas (df.describe())

Column-wise analysis:

Numeric columns → summary, mean, standard deviation, histogram

Categorical columns → frequency counts

Interactive histogram plots with Matplotlib

Beginner-friendly and lightweight web interface

## Tech Stack

Python – Core language

Streamlit – Interactive web interface

Pandas – Data handling & summary statistics

Matplotlib – Visualizations (histograms)

## Project Structure

 basic-data-analysis
 app.py # Main Streamlit app
 README.md # Documentation
 requirements.txt # Dependencies

## How to Run

Clone the repository
git clone https://github.com/your-username/basic-data-analysis.git

cd basic-data-analysis

Install dependencies
pip install -r requirements.txt

Run the app
streamlit run app.py

Upload a CSV file and explore your dataset 🎉

## Use Cases

Quick data exploration for CSV files

Generating descriptive statistics without coding

Understanding column distributions (numeric & categorical)

Lightweight tool for students, researchers, and analysts

## Author

Developed by M.Hussnain Mamoon
