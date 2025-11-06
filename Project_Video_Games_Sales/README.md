# Video Games Sales Forecasting

Project Description:
You work for the online store Ice, which sells video games all over the world. User and expert reviews, genres, platforms (e.g. Xbox or PlayStation), and historical data on game sales are available from open sources. You need to identify patterns that determine whether a game succeeds or not. This will allow you to spot potential big winners and plan advertising campaigns. (The dataset contains the abbreviation ESRB. The Entertainment Software Rating Board evaluates a game's content and assigns an age rating such as Teen or Mature). 

Note. You will work with dataset from 2016 to 2017. It doesn't really matter whether you're forecasting 2017 sales based on data from 2016 or 2027 sales based on data from 2026.

Steps to complete the project:
1. Open the data and study the general information
2. Prepare the data: perform data cleaning, standardize column names, check data types, check duplicates and address missing values. Calculate the total sales for each game and put these values in a separate column.
3. Analyze the data:
    - Look at how many games were released in different years. Is the data for every period significant?
    - Look at how sales varied from platform to platform. Choose the platforms with the greatest total sales and build a distribution based on data for each year. Find platforms that used to be popular but now have zero sales. How long does it generally take for new platforms to appear and old ones to fade?
    - Determine what period you should take data for. To do so, look at your answers to the previous questions. The key criterion is that the data should allow you to build a prognosis for 2017. (Work only with the data that you've decided is relevant. Disregard previous years.)
   - Which platforms are leading in sales? Which ones are growing or shrinking? Select several potentially profitable platforms.
   - Build a box plot for the global sales of all games, broken down by platform. Are the differences in sales significant? What about average sales on various platforms? Describe your findings.
   - Take a look at how user and professional reviews affect sales for one popular platform (you choose). Build a scatter plot and calculate the correlation between reviews and sales. Draw conclusions.
   - Keeping your conclusions in mind, compare the sales of the same games on other platforms.
   - Take a look at the general distribution of games by genre. What can we say about the most profitable genres? Can you generalize about genres with high and low sales?
4. Create a user profile for each region
For each region (NA, EU, JP), determine:
   - The top five platforms. Describe variations in their market shares from region to region.
   - The top five genres. Explain the difference.
   - Do ESRB ratings affect sales in individual regions?
5. Test the following hypotheses:
   - Average user ratings of the Xbox One and PC platforms are the same.
   - Average user ratings for the Action and Sports genres are different.
   - Set the alpha value yourself and Explain:
      - How you formulated the null and alternative hypotheses.
      - What criteria you used to test the hypotheses and why.
6.  Write a general conclusion
