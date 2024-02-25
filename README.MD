# Projected Delivery Time Estimation

This Python project uses Monte Carlo simulations to project and visualize delivery timings based on historical data.

### Getting Started

These instructions will help you set up and execute this project on your local machine.

### Prerequisites

This application requires the following Python packages:
1. Pandas
2. Numpy
3. Matplotlib
4. Seaborn

Make sure all dependencies are installed by running this command in your terminal:

`pip install -r requirements.txt`

### Data Source

This project reads data from a CSV file named Jira_exported_data.csv . 
Ensure that you update the csv_file_path variable through the script with the correct path to your CSV file. 
The CSV file should contain 'Created' and 'Resolved' as column names, which reflect dates in a format compatible with pandas to_datetime function.

### Running the application

To run this application, open the .ipynb file with Jupyter Notebook and run all cells.
Modify any input parameters (like number of runs for Monte Carlo simulation) according to your needs.
Please note that the path to the CSV file and the number of runs for the Monte Carlo simulation may need to be adjusted based on your specific requirements and resources.

### Authors

Pavel Kudrautsau

### License

This project is licensed under the GNU General Public License v3.0 - see the LICENSE.md file for details

### Acknowledgments

Special thanks to Eugene Medved and Lubov Kudrenok for their support and guidance.
