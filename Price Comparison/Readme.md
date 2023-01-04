<h1>Amazon Snapdeal Price Comparison Flask App</h1>

This is a Flask App for Comparing the price of a product on Ecommerce websites. 

First open localhost:8000/search and then enter the name of the product which you want to search. 

The program then uses BeautifulSoup library and Requests Library and does web scrapping on the Snapdeal and Amazon website.

Then the program scrapes the websites of Snapdeal and Amazon and finds the top results from the website and stores them using Lists and Dictionary data structure of Python

The program then redirects you to localhost:8000/result and displays the results of Snapdeal and then of Amazon in a table.

The program also uses routing to to redirect you to different web pages of the app like home page, search page and results page

To use it, first write this command in the command line

pip install -r requirements.txt

To run the file write

python app.py

Open web browser and go to localhost:8000/search and enter name of the product that you want to search.
You will be redirected to localhost:8000/result and Snapdeal and Amazon search results will be shown to you for that product.
