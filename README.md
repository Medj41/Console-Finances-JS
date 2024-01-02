# Console-Finances-JS

Console-Finances
This repository, Console-Finances, contains a JavaScript application that analyzes financial data from a given dataset. The following analyses have been implemented:

Total Number of Months:

The application calculates the total number of months included in the dataset.
Net Total Amount of Profit/Losses:

It computes the net total amount of Profit/Losses over the entire period.
Average Changes in Profit/Losses:

The code tracks the changes in Profit/Losses from month to month and calculates the average (Total/(Number of months - 1)).
Greatest Increase in Profit/Losses:

It identifies the month and amount of the greatest increase in Profit/Losses over the entire period.
Greatest Decrease in Profit/Losses:

Similarly, the application determines the month and amount of the greatest decrease in Profit/Losses.
Instructions
This repository has already been set up and includes the necessary files and code for the financial analysis. If you'd like to use this application, follow these steps:

1. Clone the Repository
bash
Copy code
git clone  
<!-- git@github.com:Medj41/Console-Finances-JS.git -->
cd Console-Finances
2. Dataset Included
The starter files, including the dataset composed of arrays with two fields (Date and Profit/Losses), are already present in the repository.

3. Run the Application
Open the index.html file in your preferred web browser. This will execute the JavaScript code and display the analysis results in the browser console.

Sample Output
Upon running the code in the browser, the analysis results will be displayed in the console, similar to the following:

*********

Financial Analysis
-------------------
Total Months: 86
Total: $38382578
Average Change: $-2315.12
Greatest Increase in Profits: February 2012 ($1926159)
Greatest Decrease in Profits: September 2013 ($-2196167)


![js](https://github.com/Medj41/Console-Finances-JS/assets/127996990/5ad6980b-ebfe-4561-84b8-ba435b2585a0)

![Alt text](URL "js.png")
Code Structure
The primary JavaScript code is located in the script.js file. It reads the dataset, performs financial analysis, and logs the results to the console. The code is well-commented for better understanding.


Dataset Format
Ensure that your dataset adheres to the specified format with arrays containing Date and Profit/Losses fields. If needed, you can replace the provided dataset with your own financial data.

Happy analyzing! If you have any questions or feedback, feel free to open an issue on this repository.







