# Browser puppetry: Playwright for dynamic website scraping

a.k.a. "Using Playwright to scrape pages that require you to fill out forms"

## DataHarvest 2025, Mechelen

Jonathan Soma, Knight Chair in Data Journalism at Columbia Journalism School

**Contact:** [jonathan.soma@gmail.com](mailto:jonathan.soma@gmail.com) / [@dangerscarf](https://twitter.com/dangerscarf) / [jonathansoma.com](https://jonathansoma.com/)

## What is this?

Playwright is a next-generation browser automation tool that allows you to use Python or JavaScript to scrape almost any web page. It can assist in downloading pages of government documents, capturing tweets before they get deleted, or simply breaking past the cookie consent banner. Beyond the basics, it can also easily take screenshots, monitor and log network requests, and even fit right into your traditional BeautifulSoup scraping approach.

> **Note for Windows:** For some reason only one particular version of one particular thing works on Windows, so you need to run `pip install ipykernel==6.28.0` before running Jupyter. The explanation is long and complicated. Also, maybe doing that [breaks some things](https://github.com/ipython/ipykernel/issues/1190)? It honestly isn't clear.

## The examples

- [Syllabus books](00-OpenSyllabus.ipynb): selectors, pagination
- [Texas Tow Trucks Licenses](01-Texas%20Tow%20Trucks%20Licenses.ipynb): dropdowns
- [Iowa Appraisal Management Companies](02-Iowa%20Appraisal%20Management%20Companies.ipynb): dropdowns, 'next page' buttons
- [North Dakota Oil Wells](03-North%20Dakota%20Oil%20Wells.ipynb): dropdowns, using every dropdown option
- [Maryland Locksmiths](04-Maryland%20Locksmiths.ipynb): text boxes, inspecting pages, lists of inputs (zip codes), back button
- [Texas Medical Board Actions Details](05-Texas%20Medical%20Board%20Actions%20Details.ipynb): text fields, clicking links, downloading files, changing browsers, lists of inputs (license numbers)

## More links

If you'd like a general-purpose introduction to Playwright [try this one](https://jsoma.github.io/advanced-scraping-with-playwright/), and if you want to know how to break CAPTCHAs, [here you go](https://jonathansoma.com/everything/scraping/solving-captchas-in-playwright-with-nopecha/)!

The [Playwright documentation](https://playwright.dev/python/) is also pretty good.