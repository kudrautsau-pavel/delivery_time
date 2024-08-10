# Projected Delivery Time Estimation


The Python script used in this project performs the following:
Loads data from a CSV file.
Converts relevant columns to datetime format.
Calculates the delivery time in days.
Filters rows where delivery time is zero.
Removes rows from the dataset where delivery time is zero.
Plots the distribution and calculates various statistics related to delivery time.

### Getting Started

These instructions will help you set up and execute this project on your local machine.

### Dependencies

This application requires the following Python packages:
jupyter
numpy
pandas
scipy
matplotlib


Make sure all dependencies are installed by running this command in your terminal:

`pip install -r requirements.txt`

### Data Source

This project reads data from a CSV file named Jira_exported_data.csv . 
Ensure that you update the csv_file_path variable through the script with the correct path to your CSV file. 
The CSV file should contain 'Created', Resolved', 'Issue key' as column names, which reflect dates in a format compatible with pandas to_datetime function.

### Running the application

Setup
Python 3.12.2 and the following packages are used: pandas, numpy, matplotlib and seaborn.
Have your Jira exported data in a .csv file with separators (;) in the same directory where the script is run.

### Authors

Pavel Kudrautsau

### License

This project is licensed under the GNU General Public License v3.0 - see the LICENSE.md file for details

### Acknowledgments

Special thanks to Eugene Medved and Lubov Kudrenok for their support and guidance.
