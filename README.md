# Module-11-Challenge
 Mars News and Weather Data Analysis 

## Project Overview
This project focuses on analyzing Martian news and weather data scraped from web sources. The challenge involves using Python libraries like Pandas, Beautiful Soup, and Splinter to scrape, process, and analyze data. The project is divided into the following key tasks:

1. **Scrape Titles and Preview Text**: Scraping Mars news titles and preview text from a webpage and storing them in a structured format.
2. **Scrape and Analyze Weather Data**: Extracting Mars weather data from an HTML table, analyzing it for patterns, and visualizing the results.
3. **Export Results**: Storing the processed data into CSV files for further use.

---

## Files Included
The project contains the following files and directories:
- **part_1_mars_news.ipynb**: A Jupyter Notebook that scrapes and processes Mars news data.
- **part_2_mars_weather.ipynb**: A Jupyter Notebook that scrapes, analyzes, and visualizes Mars weather data.
- **mars_news.json**: A JSON file containing the scraped Mars news data.
- **mars_weather_data.csv**: A CSV file containing the processed Mars weather data.
- **README.md**: This documentation file.

---

## Instructions for Running the Project
1. **Install Dependencies**:
   - Ensure Python is installed on your system.
   - Install the required Python libraries:
     ```bash
     pip install pandas beautifulsoup4 splinter matplotlib
     ```

2. **Run Jupyter Notebooks**:
   - Open the Jupyter Notebooks `part_1_mars_news.ipynb` and `part_2_mars_weather.ipynb` in Jupyter Notebook or Jupyter Lab.

3. **Scrape Mars News Data**:
   - Execute the cells in `part_1_mars_news.ipynb` to scrape Mars news titles and preview text.
   - The scraped data will be stored in a JSON file: `mars_news.json`.

4. **Scrape and Analyze Weather Data**:
   - Execute the cells in `part_2_mars_weather.ipynb` to scrape weather data, analyze it, and generate visualizations.
   - The analyzed data will be saved as a CSV file: `mars_weather_data.csv`.

5. **Visualizations**:
   - The Jupyter Notebook generates visualizations of the weather data, such as temperature and pressure trends over time.

---

## Breakdown of Tasks

### Part 1: Scrape Titles and Preview Text
- Scrapes Mars news data, including:
  - Titles of news articles.
  - Preview text summarizing the articles.
- Stores the data as a JSON object for structured access.

### Part 2: Scrape and Analyze Weather Data
- Scrapes Mars weather data from an HTML table.
- Analyzes weather data to answer the following questions:
  - How many months exist on Mars?
  - What are the coldest and hottest months on Mars?
  - What is the average atmospheric pressure by month?
  - How many terrestrial days exist in a Martian year?
- Generates bar charts and other visualizations to display the analysis results.

---

## Attribution and Code Sources
- This project was developed as part of a bootcamp program.
- The code for scraping and analyzing data was developed using Python libraries and class resources.
- Class materials, documentation, and external resources were used to complete this challenge.

---
