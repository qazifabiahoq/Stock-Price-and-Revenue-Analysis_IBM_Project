# IBM Python Data Science Project: Stock and Revenue Analysis
## Overview
This project is part of the IBM Python for Data Science course and demonstrates the application of data science techniques to analyze the stock performance and revenue trends of various companies, including Tesla, GameStop, Apple, AMD, and Amazon. The project uses historical stock data, web scraping, data visualization, and statistical analysis to uncover insights into the companies' financial health, stock movements, and revenue trends.

The analysis is broken down into three main notebooks:

Notebook 1: Tesla, Apple, and AMD Stock & Revenue Analysis
Notebook 2: Amazon Stock Analysis with Web Scraping
Notebook 3: Comparative Analysis of Tesla vs. GameStop
## Technologies Used:
Python: Programming language for data analysis and visualization.
Pandas: For data manipulation and cleaning.
BeautifulSoup: For web scraping and extracting information from web pages.
Plotly: For interactive visualizations of stock prices and revenues.
Matplotlib: For basic data visualizations.
Jupyter Notebooks: For creating and documenting the analysis.
## Project Breakdown
### Notebook 1: Tesla, Apple, and AMD Stock & Revenue Analysis
Tesla Stock & Revenue Analysis
In this first part of the project, I analyzed Tesla’s stock price and revenue data to visualize how the company’s stock price and revenue have evolved over time:

Tesla Stock Price: Using historical stock data, I plotted Tesla's stock price, showing a clear increase starting in February 2020, with a gradual rise over the years. This steady growth is attributed to Tesla's market share expansion and the growing investor confidence in electric vehicles.

Insight: Tesla's consistent stock price increase aligns with its business success and increasing adoption of its electric vehicles and other technologies.
Tesla Revenue: I visualized Tesla's revenue growth, which showed a steady increase over the years, reinforcing the company’s performance in the market.

Insight: Tesla’s revenue growth matches the rise in its stock price, suggesting a healthy correlation between the company’s financial performance and market valuation.
Apple Stock & Dividend Analysis
For Apple, I analyzed its historical stock price and dividend payouts:

Apple Stock Price: Using the command apple_share_price_data.plot(x="Date", y="Open"), I observed a gradual increase in Apple's stock price since 2010. The rate of increase became steeper as the company expanded globally and increased its product offerings.

Insight: Apple’s steady growth in stock price reflects its consistent performance and increasing market presence.
Apple Dividends: The second analysis involved plotting Apple's dividend payouts with the command apple.dividends.plot(). I found that dividends fluctuated starting from 2011, but the overall trend was an increase over time.

Insight: Apple’s ability to steadily increase dividends reflects its strong financial standing, supporting long-term investor confidence.
AMD Stock Analysis
For AMD, I focused on obtaining and analyzing historical stock data:

Historical Data: I used the amd.history(period="max") command to retrieve AMD's stock data, cleaned and reset the index for easier analysis.

Volume Traded: I discovered that the volume traded on the first day was 219,600, indicating a high level of investor interest when AMD was first listed.

Insight: This data point provides context for understanding the initial market reaction to AMD’s listing and its early investor enthusiasm.
### Notebook 2: Amazon Stock Analysis with Web Scraping
Notebook 2 focused on Amazon’s stock analysis and involved web scraping to retrieve additional relevant financial data.

Web Scraping with BeautifulSoup
BeautifulSoup Web Scraping: In this notebook, I used BeautifulSoup to scrape live data from the web. I retrieved Amazon’s most recent stock price, along with other financial metrics that were not readily available through traditional APIs.

Amazon Stock Price: I then used the amazon_data['Open'].iloc[-1] method to find the latest stock price, which was $656.29 at the time of analysis.

Insight: The stock price further confirmed Amazon’s dominant position in the market and its consistent growth over the years.
Web Scraping Insights
Through web scraping, I was able to gather more granular details about Amazon’s stock performance, including information on:

The latest stock price.
Additional financial data, such as market trends and earnings reports that are not always directly available in basic stock datasets.
This allowed me to enrich the analysis and ensure the data reflected the most up-to-date information available, giving a clearer picture of Amazon's stock performance.

### Notebook 3: Comparative Analysis of Tesla vs. GameStop
In Notebook 3, I conducted a comparative analysis between Tesla and GameStop, focusing on the differences in stock behavior, revenue trends, and market events that influenced their prices.

Stock Price Trends
Tesla Stock Price: Tesla’s stock price showed a steady increase over the years, beginning from February 2020, when the price started to gradually climb, reflecting strong growth and innovation within the company.

GameStop Stock Price: In stark contrast, GameStop’s stock price exhibited a sharp, sudden rise in early 2021, driven by a short squeeze triggered by retail investors. This resulted in a steep and unsustainable spike in the stock price, followed by an equally sharp decline.

Insight: Tesla’s price growth is supported by business fundamentals, whereas GameStop’s rise was more speculative, driven by external factors like social media trends.
Revenue Comparison
Tesla Revenue: Tesla’s revenue showed a consistent increase over the years, supporting the steady growth in its stock price. The company has built a strong business model around electric vehicles, energy solutions, and expanding production capabilities.

GameStop Revenue: In contrast, GameStop’s revenue was highly volatile, reflecting the struggles of a company heavily reliant on physical retail and gaming hardware sales, both of which were significantly impacted by the rise of digital gaming and online sales.

Insight: Tesla’s revenue growth aligns with its stock performance, while GameStop’s fluctuating revenue reflects its declining business model before the stock price surge.
Detailed Findings and Insights
Tesla vs. GameStop:
Tesla’s Stock Price: Tesla’s gradual rise in stock price is driven by consistent revenue growth, technological advancements, and investor confidence in the electric vehicle market.

GameStop’s Stock Price: GameStop’s stock price showed an unsustainable spike due to external market events such as the short squeeze in early 2021, fueled by retail investors and social media campaigns.

Revenue Comparison: Tesla’s consistent and steady revenue growth aligns with its stock price increase, whereas GameStop’s fluctuating revenue mirrors its volatile stock price.

## Conclusion
This project provided an in-depth exploration of the stock and revenue data of Tesla, GameStop, Apple, AMD, and Amazon. By analyzing historical stock prices, web scraping data, and revenue trends, I was able to uncover valuable insights about each company’s market behavior and performance.

The comparison between Tesla and GameStop showed the contrast between a company’s steady growth (Tesla) and one driven by speculative trading (GameStop). This comparison highlights the importance of understanding the underlying factors that drive stock price behavior and the potential risks associated with volatile stocks.

## Future Work
Expanding the analysis to include other companies and industries to draw more comprehensive conclusions about stock price behavior.
Implementing machine learning models to predict future stock price movements based on historical data.
Enhancing the web scraping techniques to gather additional financial metrics and real-time data for more accurate stock analysis.
Instructions to Run the Project
Clone the repository to your local machine.
Install the necessary dependencies, such as Pandas, Matplotlib, Plotly, BeautifulSoup, and other Python packages used in the notebooks.
Open the notebooks in a Jupyter Notebook environment and run the cells to visualize the stock price and revenue data.
Analyze the plots and insights generated to draw conclusions on the stock performance of each company.
