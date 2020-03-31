# Reddit Headline Scraper

_31 March 2020_

Following on from the Premier League scraper, we built a dynamic scraper that grabs Reddit news headlines.

This is a dynamic web scraper; for a static web scraper, see my My First Web Scraper repository.

### Dependencies:

- Puppeteer: Node library that runs a headless Chrome browser; opens up the page and lets its dynamic elements render before scraping
- Cheerio: Node library that lets us navigate the DOM with Node and use selectors to pull elements/text out (docs: https://cheerio.js.org/)

### How to run:

- In console, run: **node reddit-scraper.js**
