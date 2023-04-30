# Nintendo Switch Game Sales and Reviews

This is a Python Project made with Jupyter lab, needing to use it to run this file, this project aimed to scrape sales data from Wikipedia while also scraping review data from Metacritic, this project includes some data cleaning, transformations, and data visualization to give insights into Nintendo's top selling games, through the use of a cut off feature, the user is able to select the year and month up to which they wish to see the sales for.

 ### This project has the following Features

    Data Extraction:
        Scrapes sales data of Nintendo Switch games from a Wikipedia page.
        Converts and cleans the scraped data, including parsing dates and numeric values.
        Generates Metacritic URLs based on the game titles for further data extraction.

    Data Transformation:
        Fetches review data from Metacritic asynchronously using aiohttp and asyncio.
        Extracts relevant review details like meta score, user score, and ratings.
        Normalizes and combines sales and review data, calculating additional metrics like score difference and combined score.

    Data Analysis:
        Ranks games based on sales.
        Merges sales data with review data.
        Visualizes the top 10 best-selling Nintendo Switch games with a bar chart.

    Data Export:
        Saves the final data, including all metrics and rankings, to an Excel file.