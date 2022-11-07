# Nutrition scraping
### This is a script which allows you to gather nutritional information of several food from a web page using web scraping techniques. 
### It was built with beautiful soup library the process consisted in:
#### 1- Gather all web page info to parse.
#### 2- Get tags and classes to inspect code.
#### 3- Create list of all urls to get into each one and get main food categories.
#### 4- Create list of url to have each sub category.
#### 5- Gather all code inside each sub category web page (e.g: "https://www.fatsecret.cl/calor%C3%ADas-nutrici%C3%B3n/gen%C3%A9rico/soda")
#### 6- Through tags (tr - to tables) got all data from tables
#### 7- Clean data
#### 8- Create an empty data frame with the colmuns needed and then i created a function to convert list into dictionary. After that  using the dictionary keys related to columns i filled data frame.
#### 9- using to nested for loops perfomr all the previous process to all data inside web page.
#### 10- Output is an excel sheet
