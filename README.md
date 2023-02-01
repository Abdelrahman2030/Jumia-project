# Project description

The goal of this project was to create a program that collects information about products on the first page of Jumia (an e-commerce store ) and saves this data in a table and save it on a CSV file

The idea of the program:

The user enters the search keyword that he wants to use, then the program converts this keyword into an URL then opens the source of this URL using Requests library, then collects the ( name, price, discount, price after discount, and rating) for all the products that appear in the first page then put this data in Pandas data frame then saves the data frame as a CSV file

steps to create this program:

- First, web scraping
In the first step i used BeautifulSoup and pandas to web scrap and find the HTML tags that holds the data that I was looking for


- Second, creating the program
after finding the names and classes of the tags that hold the data i need, i wrote my program on my text editor, and this programs contains a loop that iterate over all the HTML tags for the products in the first page, then saves these data on a CSV file on the desktop.
