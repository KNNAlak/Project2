# Project2

I would like to extract some useful data from the HTML content. The soup object contains all the data in the nested structure which could be programmatically extracted. In my project, I am scraping a webpage consisting of some quotes. So, I would like to create a program to save those quotes (and all relevant information about them).

I went through the HTML content of the webpage which I printed using soup.prettify() method and try to find a pattern or a way to navigate to the quotes.It is noticed that all the quotes are inside a div container whose id is ‘all_quotes’. So, I found that div element (termed as table in above code) using find() method.I created a dictionary to save all information about a quote. The nested structure can be accessed using dot notation.I saved all our data in some CSV file.
