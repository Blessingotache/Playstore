# Advanced Python & MySQL Project: EL/ELT Pipeline for App Reviews

### Project Overview
* This project demonstrates an advanced ETL (Extract-Transform-Load) and ELT (Extract-Load-Transform) pipeline using Python and MySQL.
* It focuses on extracting reviews from an app (with low reviews) on the Play Store or App Store,
* loading the data into a MySQL database

### Features

* Data Extraction
  Scraped app reviews using Python from either the Play Store or App Store.

* Database Creation
  Utilized the mysql-connector package to create a MySQL database directly from Python.
  Ensured sensitive information, such as database credentials, is hidden or excluded for security purposes.

* Data Loading
  Structured and loaded the extracted data into specific columns in the database created.

* Sentiment Analysis
  Analyzed the reviews to classify them as positive, neutral, or negative.

* Topic Modeling 
  Extracted two pros and two cons (bugs/issues) from the app reviews using Natural Language Processing (NLP) techniques.

* Database Validation
  Verified the database creation and data insertion via MySQL Workbench.

* Data Export
  Exported the review data table from MySQL Workbench to a JSON file for further analysis or sharing.

* Version Control
  Uploaded the complete project code and JSON export file to GitHub for collaboration and visibility.


### Tools & Technologies

* Programming Language: Python

* Database: MySQL (via mysql-connector and MySQL Workbench)

* Libraries: Database Interaction(mysql-connector), Data Analysis(pandas, numpy), Web Srapping(google_play_scraper)
