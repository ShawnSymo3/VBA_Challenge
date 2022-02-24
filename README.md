# VBA_Challenge
Using VBA for Stock Analysis

#Purpose of this project
In this project we are using VBA to help us analyze the stocks we are given. There are 12 different tickers and over 3,000 rows of data. Our goal is to look at each ticker and see the total volume and return that they are getting in each year since we have two sheets from two different years. In module 2 we completed most of this work, we compiled a code that made it easy for Steve to look into the spread sheet, click a button and See the total Volume and total return but now our goal is to refractor the code so that it is more efficent but can also hold more tickers if necessary.


#Our findings
Our 2017 findings show that most of the tickers had a positive return and were safe investments. The Particular one that Steve's parents were looking into was DQ which had the greatest return of all. For the 2018 you can see that the returns were not nearly as high and the total volumes were down as well. I think some of the reason for this was because if you look at the very top of the data in the 2018 spread sheet you can see the prices went up a bit.

<img width="241" alt="Screen Shot 2020-08-01 at 7 08 54 PM" src="https://user-images.githubusercontent.com/67278193/89124294-d36b3e00-d4a3-11ea-9b9c-d3eaa93e487e.png"><img width="296" alt="Screen Shot 2020-08-02 at 9 36 13 AM" src="https://user-images.githubusercontent.com/67278193/89124295-d5cd9800-d4a3-11ea-8db7-113b351351e0.png">


#Refractoring the code
For this challenge we refractored the code so that the code would be more efficient and run faster. One of the main things we did in this refractored code that made it different was creating the three output arrays(tickerIndex and tickerVOlumes) as arrays. Having the extra array allowed us to loop through the rows, increase our tickerVolume and add the volume for the current stockticker. From that point we are able to create our if-statements to select the ticker that we are looking for each specific cell and get our total volume and return.


#The original code
The original code only initialized startingPrice and endingPrice and had us loop through all of the values, essentially making the process longer. We only had one loop and in the refractored code we have an inner and outter loop. 

#Conclusion of refractored code
The refractored code had a much quicker run time because of the changes. This is a very positive outcome and means the code is much more efficient and most likely will run better if we have more tickers.
<img width="735" alt="Screen Shot 2020-08-02 at 9 38 11 AM" src="https://user-images.githubusercontent.com/67278193/89124319-09102700-d4a4-11ea-9124-5d69c900a249.png"><img width="747" alt="Screen Shot 2020-08-02 at 9 38 44 AM" src="https://user-images.githubusercontent.com/67278193/89124320-0ad9ea80-d4a4-11ea-8820-1a9caab16890.png">
