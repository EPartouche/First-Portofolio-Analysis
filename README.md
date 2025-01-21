# Portofolio Analysis
This project represents a freely realized endeavor undertaken during Python courses as part of the ESSEC program. It showcases the practical application of Python programming skills acquired throughout the curriculum, demonstrating the student's ability to independently conceptualize and execute a project of their own design.
The project likely incorporates various Python concepts and techniques learned during the course, such as data manipulation, algorithm implementation, or perhaps even more advanced topics like machine learning or web development. By allowing students to pursue their own interests within the framework of the course, ESSEC's approach encourages creativity, problem-solving, and the real-world application of programming knowledge, preparing students for future challenges in their academic and professional careers.

# Task 1
Task 1 involved collecting data on at least 20 companies from diverse sectors. The task required gathering historical stock prices spanning the last five years, alongside the latest key financial ratios such as Price-to-Earnings (P/E) ratio, Return on Equity (ROE), and Debt-to-Equity ratio. This comprehensive dataset serves as a foundation for further analysis and insights into the financial performance and market trends of the selected companies. I decided to include some companies and sectors non-randomly (mandatory_tickers = ['AAPL', 'TSLA', 'GOOGL', 'LLY', 'UNH', 'MRK', 'EA', 'PARA', 'NWS'])

Selected 40 tickers: ['AAPL', 'TSLA', 'GOOGL', 'LLY', 'UNH', 'MRK', 'EA', 'PARA', 'NWS', 'LYV', 'WBD', 'NFLX', 'POOL', 'RL', 'APTV', 'MNST', 'K', 'CAG', 'WMB', 'HAL', 'EQT', 'STT', 'HIG', 'RF', 'WAT', 'LH', 'ABT', 'PCAR', 'AMTM', 'UPS', 'SNPS', 'CSCO', 'TXN', 'LIN', 'CTVA', 'IP', 'ARE', 'EQIX', 'EQR', 'CMS']

![image](https://github.com/user-attachments/assets/2938eaf1-d866-4560-b60d-ff769de5d96b)

# Task 2
Task 2 focused on data cleaning and preparation, a crucial step in ensuring the reliability and usability of the collected financial data. This phase involved inspecting the dataset for missing values, outliers, and anomalies, addressing them through appropriate methods such as imputation or removal. The task also required verifying data integrity by checking for duplicates and inconsistencies in time frames. Additionally, it involved calculating monthly and annual returns for each stock and normalizing stock prices for comparative analysis. Two separate DataFrames were created: one consolidating monthly returns and another for financial ratios. Finally, the task encouraged the creation of additional features, such as moving averages, volatility, or momentum indicators, which could potentially serve as predictors of future stock performance.

After inspect the data for missing values, outliers or anomalies and verified the data integrity (from 1980-12-31 to 2024-12-31), I calculate the monthly and annual returns for each stocks.
# Montly returns
***To view the months returns analysis clearly (with clear calligraphy), open the project (this is just a sample)***

![image](https://github.com/user-attachments/assets/0f1da244-62bc-4de3-8130-7a58c0ff8698)

With daily returns

![image](https://github.com/user-attachments/assets/936960b7-563b-439b-80cf-3cf4cf7f7272)


# Annual returns
# ***To view the annual returns analysis clearly (with clear calligraphy), open the project (this is just a sample)***

![image](https://github.com/user-attachments/assets/32abe853-68fe-4cc3-9559-21620d4c2355)

For each company, a specific returns analysis has been done. Here are displaying only few of them.

![image](https://github.com/user-attachments/assets/9064f725-01ca-4b3f-a83f-f5733a5e3d6a)

![image](https://github.com/user-attachments/assets/54537e41-9ac2-4e9e-a5ff-85a34fc105b2)

![image](https://github.com/user-attachments/assets/e5d49eb6-00af-4fa0-a091-e440d485d6b2)

After that, a comparasion of the performance of different stocks on similar scale has been done. Here is displaying the analysis for the entretainment companies (Electronic Art, Paramount and News Corporation) .

![image](https://github.com/user-attachments/assets/2ad08486-dc7c-408f-9197-4578b4417d1d)

![image](https://github.com/user-attachments/assets/0e3ebc99-c0ee-4527-8824-2a15aed677d5)

![image](https://github.com/user-attachments/assets/b84a9876-4a9e-4eca-8189-5dd8439b7cbf)

***Further analysis: Volatility***

![image](https://github.com/user-attachments/assets/543723ad-199f-4b55-a054-de0c1368376c)

# Create two separate DataFrames

***Subplots for Stocks Price***

![image](https://github.com/user-attachments/assets/46a5da80-abab-4ede-97e9-e79d2df7e10b)

***Average Analysis***

![image](https://github.com/user-attachments/assets/c8cead98-1e8c-452e-86f1-42300e9e79c0)

![image](https://github.com/user-attachments/assets/7a1250c1-af06-4a4e-8654-bde7fb197ab9)

![image](https://github.com/user-attachments/assets/6106940d-0839-4c1f-96f1-eb74ab234e3b)

![image](https://github.com/user-attachments/assets/14648a35-37f4-4489-9a26-01aa2b67aa57)

***Volatility Analysis***

***To view the months returns analysis clearly (with clear calligraphy), open the project (this is just a sample)***

![image](https://github.com/user-attachments/assets/a1e8875b-a336-4b1b-87d5-5dff75f3e611)


# Task 3

Task 3 focuses on Exploratory Data Analysis (EDA) of the collected financial data. It requires creating visualizations to understand stock price trends, analyzing the distribution of monthly and annual returns, and constructing correlation matrices. These analyses aim to provide insights into the behavior of selected stocks, identify patterns in returns, and reveal relationships between different stocks and financial ratios. By employing various visualization techniques and statistical analyses, this task helps in gaining a comprehensive understanding of the dataset, which can inform further analysis and potential investment strategies.


# Stock prices evolution

![image](https://github.com/user-attachments/assets/262bb100-0aa7-45b6-84b5-f408cd7b0001)

***To view the Stock prices evolution analysis clearly (with clear calligraphy), open the project (this is just a sample)***

![image](https://github.com/user-attachments/assets/4cb933c5-f18c-42aa-801f-1ffca7ad7e5f)

# Distribution of monthly and annual returns

***Only the distribution of monthly returns is displaying***

![image](https://github.com/user-attachments/assets/f0100b4b-0c0a-4d35-9b9e-ac43032c6996)


# ***Correlation matrices to identify relationships between different stocks and financial ratios***

# Correlation Heatmap

![image](https://github.com/user-attachments/assets/996621d0-719c-4faf-b63f-3c51985cff42)

# Task 4

Task 4 focuses on portfolio construction and performance evaluation. It requires the use of mean-variance optimization to build a portfolio or the application of a custom strategy for stock selection. Once the portfolio is constructed, the task involves backtesting its performance over the past two years. This process aims to assess the effectiveness of the chosen strategy by simulating how the portfolio would have performed historically. The backtesting will likely include calculating key performance metrics such as returns, risk-adjusted measures, and comparing the portfolio's performance against relevant benchmarks. This comprehensive approach allows for the evaluation and potential refinement of the investment strategy based on historical data.

# Minimum risk Portofolio Construction and then Optimized Sharpe Ratio Portofolio

![image](https://github.com/user-attachments/assets/6a6e8188-2edf-47b4-8dd3-a1c37c07f181)

![image](https://github.com/user-attachments/assets/88087733-b96e-4ccd-bc7b-c8e0d0b88fb1)

![image](https://github.com/user-attachments/assets/2526dac8-d5b5-4c24-a464-c4f9ea044042)

![image](https://github.com/user-attachments/assets/39e0aa31-c5ee-4af8-a611-fd7159d93c33)

![image](https://github.com/user-attachments/assets/d7b539f1-7ce6-4740-b532-7b1079f5b7fb)

# 1- Final Optimized Portofolio Construction - Adding restrictions: 

***- The weight in the portofolio by stock is between 3% and 25%***
***- Between 10 and 20 differents stocks with significative weight differences***
***-Expected return better than 12%***
***-Lower standard deviation than S&P 500 stocks***

![image](https://github.com/user-attachments/assets/8a0760de-e6dc-4004-976c-3e60a67b7a0e)

![image](https://github.com/user-attachments/assets/fc4a4c34-e1ee-42b2-b9a7-8e6c81289fb1)

![image](https://github.com/user-attachments/assets/3aeca17e-15e2-47ac-89b7-48a6cf7a4b14)

![image](https://github.com/user-attachments/assets/d97028f5-869e-4fd5-90d0-f06fc818a3c7)

![image](https://github.com/user-attachments/assets/0176ae1d-0a2b-4582-a24d-db0792e978b7)

![image](https://github.com/user-attachments/assets/a0813c6e-f950-4503-990d-f9440b392f2b)

# Stock Analysis (Historical Close Price - Daily Returns)

***To view the Historical Close Price - Daily Returns analysis clearly (with clear calligraphy), open the project (this is just a sample for 3 companies)***

![image](https://github.com/user-attachments/assets/f4e1d4e8-f39f-43e1-9a2e-530203390868)

![image](https://github.com/user-attachments/assets/4f5d8b34-1dbf-4ce8-82c1-6ffac3d4cd02)

![image](https://github.com/user-attachments/assets/83554724-2e10-4c51-9b67-99c020f7bb3f)

***Comparasion between the Portofolio and its market (S&P500)***

![image](https://github.com/user-attachments/assets/179209a0-7f01-43e5-a386-bd9364612821)

# ***2- Alternatively, apply your own strategy to select a combination of stocks***
***Without using the sharpe ratio, I would have set up my portofolio with two restrictions:***

*   ***Expected return superior to 20%***
*   ***Between 10 and 20 stocks***

![image](https://github.com/user-attachments/assets/078bc4c8-3d6a-469c-9336-ed013dd71590)

![image](https://github.com/user-attachments/assets/6eec0256-d4f8-4726-9826-8edbdaf1477c)

## ***3- Backtest the portfolio performance over the last 2 years***

***Step 1- Portofolio and market performances over the 2 last years***

![image](https://github.com/user-attachments/assets/fba0a945-b7f8-434e-af25-7f5fab7ea200)

![image](https://github.com/user-attachments/assets/e56832b4-d3eb-44ab-9cb1-a55df03d63e8)

***Step 2- Returns forecasted according to the expectations***

![image](https://github.com/user-attachments/assets/186cc86a-5803-4c93-b30b-521264655f72)

![image](https://github.com/user-attachments/assets/e97de83f-bcb2-42e9-8407-be5771483d41)

# Task 5











