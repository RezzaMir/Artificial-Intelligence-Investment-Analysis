# Investment Analysis (Python Modelling)

Note: This assignment uses the Excel data file titled Modelling Assignment 4 Data File.xlsx (Date File) found on ACORN.  You will also need to download Python and related software to complete this assignment.  Please see the Python Lab videos on ACORN for instructions on software installation.

# Assignment Set Up
The output for this assignment will be the Jupyter Notebook file that you create in making the model below.  Save this file in the same format as you used for prior assignments (for example, MacLean-Davis-Assignment4).  Note that the file extension will not be “.xlsx” as this is for Microsoft Excel.  Your file extension will be “.jpynb”.

All calculations must be done within Python.  The Data File has been ‘pre-cleaned’ for you so no formatting, calculations or data clean-up in Excel is required.  I will be running your Python code against the original Data File, so any data manipulation outside of Python will not be capture and your code will most likely fail.

Be sure to use labels and text within the Notebook so that each model is clearly labeled.  Only submit one Notebook file for the entire assignment, not one Notebook per individual model.

# Model 4a: Python Risk and Return Calculations
Create a model in Python that allows the user to enter a ticker from the Data File and Python will return each of the following:

i.	Annualized Arithmetic Return
ii.	Annualized Geometric Return
iii.	Annualized Volatility
iv.	Skewness of Weekly Returns
v.	Excess Kurtosis of Weekly Returns
vi.	Coefficient of Variation
vii.	90% Confidence Interval of Annual Returns
viii.	A graph representing the growth of $100 invested in the specific stock on the first day in the sample through the last day in the sample

# Model 4b: Python Basic Stock Comparison
Create a model in Python that allows the user to be able to enter two tickers from the Data File and Python will return each of the following for the two stocks, indicating which of the two is preferred:

i.	Annualized Geometric Return
ii.	Annualized Volatility
iii.	Coefficient of Variation

# Model 4c: CAPM in Python 
Create a model in Python as follows:

i.	The user can enter a ticker from the Data File and Python will return that stock’s beta.
ii.	The user can then enter the risk-free rate and an epexcted market return and the model will calculate the expected return for the user selected stock.
