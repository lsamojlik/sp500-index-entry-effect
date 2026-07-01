________________________________________
<div align="center">

<b>
A Company's Inclusion in a Prestigious Index - a receipe for "Easy" Profit or a trap for less experienced investors?</b>

</div>

________________________________________
youtube video: https://www.youtube.com/watch?v=waVLqRRszhY


**Problem Description**:

Index revisions carry significant implications for companies – shares of firms added to an index must be reweighted by passive funds, generating additional demand for the company’s stock.



Moreover, companies entering the index are typically in a strong upward momentum phase (which often supports trend continuation), their financial condition is generally stronger than a few quarters earlier, and increased visibility may serve as an additional catalyst for future price appreciation.



Using data on changes in the composition of the S&P 500 from 1996–2025, I examined how the stock prices of companies added to the index behaved. The analysis covered both the period preceding inclusion and the period after the inclusion became effective (effective date).


**Assumptions**:

- On the inclusion date, the Adjusted OPEN price was used. The adjusted price accounts for all corporate actions that could distort the data, such as splits and dividends. This prevents artificial price movements.

- All other stock prices used in the analysis are Adjusted CLOSE prices from 5 trading days prior, 20 trading days prior (treated as 1 month prior), 60 trading days prior (treated as 3 months prior), 20 trading days forward (treated as 1 month forward), and 60 trading days forward (treated as 3 months forward).

- Companies that were delisted were not included in the study due to limitations of the free version of Yahoo Finance.

- S&P 500 data retrieved using the ticker ^GSPC reflect analogous time shifts to those applied to the companies entering the index.



**Data Sources**:

- yfinance library (Yahoo Finance)

- Kaggle – S&P 500 index constituents (including historical changes)

________________________________________

**Summary and Investor Takeaways**:

1.  The 1–3 month period prior to index inclusion historically exhibited strong momentum and high relative returns compared to the benchmark.

2.	The period immediately following index inclusion (1M–3M) did not statistically provide an advantage over the market – momentum often slowed and mean reversion occurred.

3.	The short window around the announcement date generated positive returns mainly in earlier years; after 2010, the effect weakened noticeably.

4.  The key challenge remains accurately identifying which company will ultimately be added to the index.
