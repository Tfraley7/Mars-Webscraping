# News Scraping

* In this activity, you will scrape news summaries across multiple pages, all with an automated script.

* Go to the Global Voices news [site](https://globalvoices.org/page/2/) to inspect it.

* Your web scraping script should perform the following tasks:

  * Click on any popup or light box to make it disappear.

  * On any given page, scrape the **title** and the **date** of each article.

  * For each article summary, the title and the date should be structured as a dictionary. All dictionaries should be contained in a Python list.

  * Click the button to go to the next page of older articles, and scrape the article summary on that page as well. Repeat the process for a total of five pages.

  * Import the scraped data (a list of dictionaries) into a Pandas dataframe. Using Python, Pandas, or both, convert the dates into a useable datetime type.

* Remember that you should begin on page 2, and move on to older stories.

* Below is an abbreviated example of what your scraped data might look like.

```python
[{'header': 'Portugal: Human rights activist fighting racism wins international award',
  'date': '29 _12 2021'},
 {'header': 'Where is Qatari human rights defender Noof Al-Maadeed?',
  'date': '29 _12 2021'}]
```
