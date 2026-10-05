# Minas Gerais Toll Data Scraper

A small Python scraper that extracts toll-plaza details from a public web page and exports a structured spreadsheet.

## Data collected

The script parses highway, kilometer marker, location, axle count, and listed toll-fee information from its configured source.

## Stack

Python, Requests, BeautifulSoup, Pandas, and OpenPyXL.

## Run locally

Install dependencies from `requirements.txt`, then run `python pedagiomg.py`. The source website can change its page structure or terms, so verify the output before relying on it.
