# Predicting Home Prices in USA based on certain factors.

The goal of the project was to find publicly available data related to supply and demand factors that influence US home prices nationally. 

This step involved researching and identifying relevant data sources like Months of supply, Unemployment, Mortgage rate, personal savings etc. These were finally taken as feature variables in our ML model.

The data source "S&P Case-Schiller Home Price Index" was used as target variable.

Data preparation is a critical step in building a data science model. During this stage, the collected data underwent :
a.  Data Cleaning: Removing duplicates, handling missing values, and correcting inaccuracies.
b.  Data Formatting: Ensuring data is in the right format and converting variables (if needed).
c.  Feature Selection: Identifying which factors are most relevant for the analysis.

Chose Linear regression Model.....fed the data and eventually trained the model.

The final step is Model Evaluation. This involves assessing how well the model predicts home prices based on supply and demand factors.

Used different metrics like Mean Absolute Error (MAE) or Root Mean Squared Error (RMSE) to measure the accuracy.

Data visualization is also done using "Residual Plots" to check the assumptions and performance of the model.

Factors affecting home prices are :
a. "Months of Supply, Homes for Sale and Homes sold" : This factor helps us understand if there are enough houses available in the real estate market for potential buyers or if there are excess or how many houses are sold. 
b. "Federal Funds Rate" It's the interest rate that banks charge each other for short-term loans, set by the Federal Reserve. When it's lowered, banks may offer lower mortgage rates, making it cheaper to borrow money for homes, which can increase demand and potentially drive up home prices. Conversely, when the rate is raised, it can make borrowing more expensive, reducing demand and potentially causing home prices to stabilize or even decrease.
c. "Personal savings" are like set aside incomes. When people save more, it can make it easier to buy homes because they have money for a down payment. However, if people save less and spend more, it can increase demand for homes and drive up prices due to more potential buyers in the market. 
d. "Disposable personal income" gives us the amount which is left to spend(buy a house) after saving and taxes. More disposable income can boost demand for homes, potentially raising prices, while less disposable income might have the opposite effect.
e. "Personal Consumption" is about how people are spending the money and to know whether they are interested to rent or buy a house.
f. "Housing starts" represent the number of new housing projects that have begun during a specific time period. More housing starts can increase the supply of homes, potentially lowering home prices, while fewer housing starts can reduce supply and potentially drive up prices.
g. "Mortgage rates": These are essentially the cost of borrowing money to buy a home. When rates are low, more people can afford homes, increasing demand and potentially raising home prices, while high rates can discourage buyers and lead to lower home prices due to decreased demand.
h. "Unemployment" affects the real estate market by reducing both the demand for homes (fewer people buying) and the supply of homes (less investment in construction). This can impact home prices by potentially lowering them due to reduced demand or raising them due to limited supply.
i. "GDP" is a measure of the health of the economy. If a country does good in GDP, then people invest more in buying houses.
j. "Construction Spending" measures how much money is being invested in building new homes during a specific time. It's also an indicator of future supply, which can influence home prices depending on market conditions.
k. "Building Permits" is like getting official permission to start a new construction. When more permits are issued, it means more homes or buildings can be constructed, potentially increasing the supply of properties in the market.
l. "Permit valuation" refers to the estimated monetary value associated with a construction or building permit issued by local government authorities. 

Feel free to explore the Jupyter Notebooks provided in this repository to gain insights into the project.
