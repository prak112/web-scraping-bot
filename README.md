# Background
This project will evolve gradually into a pre-cursor for the [text-summarizer project](https://github.com/prak112/text-summarizer). Text output from this project will be summarized using the text-summarizer.
 
In test-run, we automate extraction of 'Most Read' news items from YLE news for everyday at a fixed time. Then forward this text as an email. Also, parse the data to a CSV. Everyday's extract appends to the news items in the same CSV with date.
</br></br>

## Aim 
- Test-run the Web scraper-bot on YLE news for Most Read news items.
- Package the Scraper to extract news every day.
- Send extracted 'Most Read' news items as an email with Subject 'Headlines for Today'.
- Plan extension of scraper using API</br></br>

## Sources
### Material
- [GeekForGeeks](https://www.geeksforgeeks.org/how-to-build-web-scraping-bot-in-python/)
- [freeCodeCamp](https://www.freecodecamp.org/news/automate-your-life-with-python/)
- [YLE news](https://yle.fi/news)

### Tools & Libraries
- Python 3.9.12
- Requests 2.0.12
- BeautifulSoup (bs4 4.11.1)
- time, datetime (Python built-in)
</br></br>

## Approach
- Currently, using URL to access desired webpage
- Extract data from class_ element
- Filter content for 'Most Read' from class_ content
- Send the text as an email through an email client 

