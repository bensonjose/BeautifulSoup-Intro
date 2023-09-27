from bs4 import BeautifulSoup
import requests

url = "https://www.scrapethissite.com/pages/forms/"

page = requests.get(url)

# Specify the parser as 'html.parser'
soup = BeautifulSoup(page.text, 'html.parser')

# Print the parsed HTML
print(soup)

# Print the prettified HTML for better readability
print(soup.prettify())
