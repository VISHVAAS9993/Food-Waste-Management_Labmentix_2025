# Food-Waste-Management_Labmentix_2025
 A data-driven Food Waste Management System built using Python, SQL (SQLite), and Streamlit to reduce food wastage by connecting food providers with receivers (NGOs / individuals in need) and analyzing food distribution patterns.

Project Overview
Food wastage is a major global issue, where surplus food from restaurants and households often goes unused while many people face food insecurity. This project aims to:

Enable food providers to list surplus food

Allow receivers (NGOs / individuals) to claim available food

Analyze food distribution, claims, and wastage patterns

Provide a dashboard for insights, filtering, and CRUD operations

Project Objectives
Build a centralized food donation platform

Analyze:

Food availability

Claims and completion rates

City-wise demand and supply

Reduce food wastage using data-driven insights

Create an interactive Streamlit dashboard

Tech Stack & Skills Used
Python

SQLite (SQL)

Pandas

Streamlit

Data Analysis & EDA

CRUD Operations

Data Visualization

Project Structure
Food-Management-Analysis/

app.py / Food_Management_analysis.py # Main Streamlit application
receivers_claims.csv # Receivers & claims data
providers_foodlisting.csv # Providers & food listings
food_waste.db # SQLite database (auto-generated)
README.md # Project documentation
Key Features
Data Processing
CSV files loaded into SQLite database

Automated environment detection (local vs Streamlit Cloud)

Analysis Performed
Providers & receivers per city

Most common food & meal types

Claims by status (Completed / Pending / Cancelled)

Highest demand cities

Top contributing providers

Claim success rates

Dashboard (Streamlit)
KPI Cards:
Total Providers

Total Receivers

Total Listings

Total Claims

Claim Completion Rate

Filters:
City

Provider

Food Type

Meal Type

CRUD Operations:
Add / Update / Delete food providers

Interactive tables & charts

Visualizations Included
Food providers contribution

Claims by city

Food type distribution

Meal type distribution

Claims by provider, receiver, and status

Demand analysis by location
