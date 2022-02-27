# Houses Sales

Which houses buy to optimize the profit.

1. **Business Problem.**

The Dream House Co is a company that buy and sell houses. The main strategy is buy good houses and cheap for sell after with profit. The cheaper the better, maximize the profit.

Now a day, the decision of buy is made manually by the analysts of buy, it demand a lot of time.

It’s necessary to have an efficient analyze to help company to detect the best deals faster than possible.

There’re two main questions that will be answered:

1) Which houses should buy and at what purchase price?

2) With the house purchased, what is the best moment to sell and at what price?

1. **Business Assumptions.**
    - Don’t to buy houses price above U$ 1,027,500 because isn’t part of company strategy.
    - Houses with condition is under 3 in a scale 1 to 5 should not to be purchased.
    
2. **Solution Strategy.**
    
    My strategy to answer the business question was:
    **1. Step:** Understanding about business for clearing the business questions and the context around them.
    
    **2. Step:** Collected data and explore to identify if there are missing information in rows.
    
    **3. Step:** Identified the type of features, and converted date to format that it's possible to work.
    
    **4. Step:** Used statistical metrics to identify prices outside of business scope.
    
    **5. Step:** Answered the first question, the houses was grouped by region and calculated the median price, good conditions houses and price under median price of the region was appointed to buy, how deliverable was generated a report with the houses that should be buy.
    
    **6. Step:** Answered the second question
    The houses was grouped by region and season and then calculated the median price.
    Houses that was suggested to buy and the price was below the median price calculated above, sell price defined purchased plus 30 percent.
    Houses that was suggested to buy and the price was under the median price calculated above, sell price defined purchased plus 10 percent.
    How deliverable was generated a report with the houses and the sell price.
    
3. **Top 2 Data Insights.**
    
    **First Hypothesis:** There are good houses under median price of the region them.
    
    **True:** There are considerable amount of houses by region.
    
    **Second Hypothesis:** Houses price in the same region is different depends of the season.
    
    **True:** House prices in the same region change according to the season.
    
4. **Business Result**
    
    If used report to answer the first question to support which houses to buy, and the second report to decide what price sell, the potential profit for the company is **US$ 1,061,932,596**.