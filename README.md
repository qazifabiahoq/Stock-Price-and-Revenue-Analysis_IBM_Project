# Stock and Revenue Analysis of Leading Tech Companies

## Project Description and Dataset

This project analyzes the stock performance and revenue trends of major technology companies, including Tesla, GameStop, Apple, AMD, and Amazon. The objective is to explore how these companies' financial metrics have evolved over time, identify patterns in their stock prices and revenues, and compare their market behavior. The dataset consists of historical stock prices, company revenue reports, and web-scraped financial data sourced from official stock market records and financial websites.

## Who Will Benefit and Why

* **Investors and Financial Analysts:** Gain insights into company performance and stock trends to inform investment decisions.
* **Business Strategists:** Understand market dynamics and how revenue growth correlates with stock valuation.
* **Students and Researchers:** Learn practical applications of data science techniques such as web scraping, data visualization, and comparative analysis in finance.
* **Tech Enthusiasts:** Follow the evolving performance of leading tech firms through data-backed analysis.

## What Success Looks Like

* Clear visualization of stock price and revenue trends over time.
* Identification of factors influencing stock price movements.
* Comparative insights highlighting fundamental vs. speculative stock behavior.

---

## Methodology: How the Analysis Was Conducted

The project consists of three key parts, each implemented in a separate Jupyter notebook:

1. **Tesla, Apple, and AMD Stock & Revenue Analysis:**

   * Historical stock data was obtained and cleaned using Python and Pandas.
   * Stock price and revenue trends were plotted using Plotly and Matplotlib for visual clarity.
   * Dividend and volume traded data were analyzed for additional financial context.

2. **Amazon Stock Analysis with Web Scraping:**

   * BeautifulSoup was employed to scrape Amazon's latest stock price and supplementary financial details from the web.
   * Scraped data enriched the stock analysis, ensuring up-to-date insights.

3. **Comparative Analysis of Tesla vs. GameStop:**

   * Stock prices and revenue trends were compared side-by-side to highlight differences between steady business growth (Tesla) and speculative market activity (GameStop).
   * Key market events impacting stock behavior were incorporated into the interpretation.

---

## Key Findings

1. **How has Tesla’s stock price evolved over time?**
   Tesla’s stock price shows a steady increase beginning in early 2020, reflecting growing investor confidence and expanding market share in electric vehicles.

2. **Is there a correlation between Tesla’s revenue and stock price?**
   Yes, Tesla’s revenue has steadily increased alongside its stock price, indicating a strong business foundation supporting market valuation.

3. **What trends are observed in Apple’s stock and dividends?**
   Apple’s stock price has gradually risen since 2010, with dividend payouts showing an overall increasing trend, signaling solid financial health and investor returns.

4. **What insights were gained from AMD’s stock volume?**
   The first trading day recorded a volume of 219,600 shares, reflecting high initial investor interest.

5. **How did Amazon’s latest stock price compare to historical trends?**
   The web scraping revealed a latest stock price of \$656.29, confirming Amazon’s continued market dominance and growth.

6. **What explains the difference in stock price behavior between Tesla and GameStop?**
   Tesla’s growth is driven by consistent revenue increase and innovation. GameStop experienced a sudden, sharp spike due to a short squeeze influenced by retail investors, followed by a rapid decline.

7. **How do Tesla and GameStop revenue trends compare?**
   Tesla’s revenue shows steady growth supporting its stock price, whereas GameStop’s revenue is volatile, reflecting struggles in adapting to changing market conditions.

---

## Conclusion

This analysis highlights how steady business fundamentals lead to sustainable stock price growth, as seen with Tesla, Apple, and AMD. In contrast, speculative factors can cause abrupt, unstable stock price movements, exemplified by GameStop. Integrating web scraping provided real-time data that enriched the stock analyses. Understanding these dynamics is essential for informed investment and market strategy decisions.

---

## Recommendations

Future analyses could broaden the scope by including additional companies and industries for a more comprehensive market perspective. Applying machine learning models to predict stock movements and enhancing data collection with real-time scraping could improve accuracy and usefulness. These steps will strengthen financial forecasting and decision-making capabilities.

---

## How to Run the Project

1. Clone the repository locally.
2. Install required Python packages: Pandas, Matplotlib, Plotly, BeautifulSoup, and Jupyter Notebook.
3. Open the notebooks in Jupyter Notebook and execute the cells sequentially.
4. Review the generated visualizations and insights for each company’s stock and revenue analysis.

---

# Technologies Used

* Python for data processing and analysis
* Pandas for data manipulation
* BeautifulSoup for web scraping
* Plotly and Matplotlib for data visualization
* Jupyter Notebooks for documentation and execution
