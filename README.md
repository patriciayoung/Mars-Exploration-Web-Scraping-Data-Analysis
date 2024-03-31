# Mars-Exploration-Web-Scraping-Data-Analysis

# Overview:
In collaboration with the food magazine "Eat Safe, Love," this project entails a thorough analysis of the UK Food Standards Agency's hygiene ratings. By employing web-scraping techniques using Splinter and HTML parsing with Beautiful Soup, alongside data analysis skills, the objective is to extract and scrutinize the food hygiene ratings data from various establishments across the United Kingdom. The insights garnered from this endeavor will inform future articles of the magazine, assisting in guiding their readers toward the best and safest dining experiences.

# Objectives:
Scrape Titles and Preview Text from Mars News: Extract news titles and preview text from the Mars News website, organizing the data into a structured Python data structure.
Scrape and Analyze Mars Weather Data: Gather weather data from a Mars Temperature Data Site, analyze the data to comprehend the Martian climate, and present the findings visually.

# Methodology:
Part 1: Web Scraping
Employed automated browsing with Splinter to navigate the Mars News site and extract titles and preview texts using Beautiful Soup.
Each title-and-preview pair was stored in a Python dictionary within a list; however, inadvertently, the entire HTML element was included instead of just the text.

Part 2: Data Analysis
Extracted Mars weather data from an HTML table into a Pandas DataFrame, ensuring accurate data types for each column.
Analyzed the dataset to ascertain the number of Martian months, the volume of available data in Martian days, the coldest and warmest months on Mars, and the months with the lowest and highest atmospheric pressure.
Developed data visualizations to support each analysis question and exported the DataFrame to a CSV file for further utilization.

# Key Findings:
Successfully scraped and retrieved Mars news titles and previews, albeit with an oversight in data structuring.
Conducted a comprehensive analysis of Mars weather data, uncovering significant trends in temperature variations and atmospheric pressure throughout various Martian months.
Visualized the average minimum daily temperature and daily atmospheric pressure for all Martian months, offering clear insights into the Martian climate.

# Conclusion:
This project underscores the effectiveness of web scraping and data analysis in extracting and examining web data for practical purposes. The insights garnered from the Mars Exploration Web Scraping and Data Analysis project will be instrumental in shaping the content strategy of "Eat Safe, Love" magazine, enabling them to prioritize articles on establishments with top-tier food hygiene ratings.
