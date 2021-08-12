# Web_scraping_with_Python
### Web Scraping and Stock price analysis using Python and Beautiful Soup

Being an early stage investor and curious about the stock market analysis. This project includes the data collection of the Stock company from the yahoo finance website using web scraping with Beautiful Soup and Python. 

`url = 'https://in.finance.yahoo.com/quote/ORIENTCEM.NS/history?p=ORIENTCEM.NS'`

`headers = {'User-Agent': 'Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/92.0.4515.131 Safari/537.36'}`

`data = requests.get(url, headers = headers, timeout=5).text`

`soup = BeautifulSoup(data, 'html5lib')`


### Collected data were transferred into a DataFrame and the Candlestick chart was build using Python.
 
![Orient](https://user-images.githubusercontent.com/69073063/129231978-dd58ecf3-e75e-4cc2-902c-39d2bba6fbcb.png)
