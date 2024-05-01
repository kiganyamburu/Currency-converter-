
# Currency Converter
This is a simple currency converter application that allows users to convert amounts from one currency to another. The application uses the forex-python library to fetch the latest exchange rates.

## Installation
To install the required libraries, run the following command:

## bash
Copy code
pip install forex-python
## Usage
To use the currency converter, run the CurrencyConverter.py script. A GUI window will appear with options to select the currencies and enter the amount to convert.

### Currency Converter Screenshot


### The application supports the following currencies:

USD - United States Dollar
EUR - Euro
JPY - Japanese Yen
CAD - Canadian Dollar
GBP - British Pound
CHF - Swiss Franc
NZD - New Zealand Dollar
AUD - Australian Dollar
KSH - Kenyan Shilling
After selecting the currencies and entering the amount, click the "Convert" button to see the converted amount.

## Error Handling
The application handles the following errors:

If the user enters a non-numeric value in the amount field, the application will display an error message "please enter a valid number!".
If any other error occurs during the conversion, the application will display an error message "Error occurred".
