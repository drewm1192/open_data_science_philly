#README

This project allows a user to upload three data files (populations.txt, parking.csv, and properties.csv) and quickly obtain metrics on life in Pennsylvania as it pertains to parking tickets and property values. All data comes from the Open Data Philly Project.

The program features a modular design using an N-tier architecture. 

To run the program, open it in Eclipse or another Java IDE, and set your runtime arguments as follows:

csv parking.csv properties.csv population.txt log.txt

Note that "csv parking.csv" can be replaced with "json parking.json" if you would like to run the JSON file instead. Both files provide the same data, but the option is provided to showcase the use of different parsers.

Please also be sure to add the provided .jar file to your Build Path.

After hitting "run", please wait for a few moments for the data to load. Once data is loaded, follow the prompts in the console.
