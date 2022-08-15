# ICT_4370_Portfolio_Assignment
Holds the portfolio assignment for ICT 4370

The stockEarnings project was designed to help a user track their stock portfolio.
The project consists of five Python files that run the application. Three of the files
are modules that hold classes. The Stock class is meant to hold data of a single stock 
belonging to an individual. The Investor class describes that individual, and each 
Stock object holds information like stock purchase price and number of stocks purhcased
by a single Investor object. The Bond class inherits from the Stock class and includes 
extra attributes that help differentiate an object as a Bond object. The Portfolio class
includes methods and attributes that enable the application to track several aspects
of the stocks included in an individuals portfolio. Methods in the Portfolio class
allows data from either a given JSON file or the yahoofinancials library be used as 
tracking data. There are methods included that store significant data into a simple 
SQLite database and also chart closing costs on a line graph using the Matplotlib
library. A chart can be created for either JSON file or yahoofinancials data. 
