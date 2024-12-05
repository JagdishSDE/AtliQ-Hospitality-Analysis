Overview 📁
This project provides a data analytics and visualization pipeline for a hotel booking dataset. It focuses on cleaning and preprocessing raw data, analyzing key metrics, and creating visualizations to derive meaningful insights. The dataset includes information such as booking details, stay duration, revenue, and guest ratings.

Features ✨
🛠️ Data Cleaning and Preprocessing
📅 Converts date columns (booking_date, check_in_date, checkout_date) into a standard datetime format with error handling.
🧹 Fills missing values in critical columns like ratings_given and converts them to appropriate data types.
🔄 Standardizes categorical columns (booking_status, booking_platform, room_category) for consistency.
➕ Adds new metrics:
stay_duration: Calculates the duration of each stay.
revenue_per_guest: Computes revenue generated per guest.

📈 Exploratory Data Analysis
Revenue Analysis:
💰 Total revenue generated and realized.
📊 Breakdown of revenue by booking platform.
Occupancy Insights:
📅 Monthly trends in guest check-ins.
🔢 Overall occupancy rate calculation.
Guest Ratings:
⭐ Average ratings categorized by booking platform.


📊 Visualizations
📊 Bar plot for revenue distribution across booking platforms.
📈 Line plot showcasing monthly occupancy trends.
🥧 Pie chart displaying the distribution of booking statuses.


💾 Data Export
Saves the cleaned and preprocessed dataset for further analysis.


Directory Structure 🗂️
fact_bookings.csv: Raw dataset.
cleaned_dataset.csv: Preprocessed dataset.
Script file: Python code for data analysis and visualization.






