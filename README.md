# Article Scraping and Analysis
## Overview
In this analysis, we focused on scraping and analyzing news articles related to Mars using web scraping techniques. We utilized Python's Beautiful Soup library to extract relevant information from the web pages and organized the data for further analysis. The purpose was to create a concise summary of the articles and present them in a structured format.

## Scraping News Articles
We began by automating browsing using the Splinter library to visit a website containing Mars-related news articles. We then used Beautiful Soup to parse the HTML content and extract relevant details such as the publication date, title, and preview of each article. The information was stored in a dictionary format, making it convenient for further processing.

### Analysis
After scraping the articles, we had a collection of news pieces covering a range of topics related to Mars exploration. We presented the information in a tabular format, providing a snapshot of each article's key details. This approach allowed for easy comparison and quick access to the most important information within each article.

# Mars Weather Data Scraping and Analysis
## Overview
The second part of the analysis involved scraping and analyzing Mars weather data. We aimed to extract temperature and atmospheric pressure data from a web page and conduct various analyses to gain insights into the Martian climate.

### Scraping Mars Weather Data
We used automated browsing to access the Mars Temperature Data website and utilized Beautiful Soup to parse the HTML content. The relevant data, including temperature, pressure, and other attributes, were extracted from the HTML table and organized into a Pandas DataFrame.

### Analysis
With the Mars weather data organized in a DataFrame, we performed a series of analyses to better understand the climate on Mars:

Number of Months on Mars: We calculated the number of unique Martian months present in the dataset, giving us an idea of the data's timespan.

Martian Days' Worth of Data: We determined the number of Martian days represented in the dataset, providing insight into the data's temporal coverage.

Average Low Temperature by Month: We calculated the average minimum temperature for each Martian month and visualized the results using a bar chart. This allowed us to identify temperature trends over the months.

Coldest and Warmest Months: By analyzing the average minimum temperatures, we identified the coldest and warmest months on Mars, providing insights into its seasonal variations.

Average Atmospheric Pressure by Month: We calculated the average daily atmospheric pressure for each month and visualized the data using a bar chart. This helped us understand pressure patterns over the months.

Terrestrial Days in a Martian Year: By estimating the number of terrestrial days in a Martian year, we provided a perspective on the time difference between Earth and Mars.

## Conclusion
Through scraping and analyzing both news articles and Mars weather data, we gained valuable insights into ongoing Mars exploration efforts and the Martian climate. The use of web scraping techniques and data analysis tools allowed us to process and present complex information in a comprehensible and structured manner. This analysis contributes to our understanding of Mars and its exploration, as well as showcasing the power of Python libraries in data collection and analysis.

##### References
###### The Mars News websiteLinks to an external site. is operated by edX Boot Camps LLC for educational purposes only. The news article titles, summaries, dates, and images were scraped from NASA's Mars NewsLinks to an external site. website in November 2022. Images are used according to the JPL Image Use PolicyLinks to an external site., courtesy NASA/JPL-Caltech.

###### All codes used in this project are from week 11 classes, and troubleshooting was done with the assistance of Chat-GPT
