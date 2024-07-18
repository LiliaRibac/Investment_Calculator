Investment Calculator

The Investment Calculator is a React application that allows users to input investment parameters and view detailed results over the investment period. The app includes features for displaying a header, fetching user input, and outputting the results in an HTML table. It leverages a provided utility function to derive investment results and conditionally displays an information message if an invalid duration (< 1 year) is entered.

Features

* Header Component: Displays the title and brief description of the application.
  
* User Input Component: Collects investment parameters from the user.

* Results Table Component: Displays the calculated investment results in a structured HTML table.

* Validation: Shows an informational message when an invalid duration (< 1 year) is entered.
  
* Data Storage: Stores the entered investment parameters for processing and display.
  
Usage

1. Input Parameters: Enter the initial investment amount, annual interest rate, and investment duration.
   
2. View Results: See the investment year, investment value, interest earned, total interest, and invested capital for each year in the results table.
   
4. Validation: Receive feedback if the entered investment duration is less than one year.
   
Technologies

React,
HTML,
CSS
