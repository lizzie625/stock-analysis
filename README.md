# stock-analysis

Overview:

We have created an efficient workbook for our client, Steve, who is interested in buying some stock. His parents suggested he should buy "DQ" but they all would like some research done to ensure that it is a smart buy.We did some analysis on "DQ" but are going a step further to compare it with similar stocks. We created some code that will allow Steve and his parents to analyze data in multiple ways to help them make an economical decision.We made sure to create an analysis that was easy for Steve and his parents to understand and manipulate without having to do much work. Our goal is that this analysis can help him analyze the dataset of the stock he is interested in and compare it to similar stocks to his satisfaction. We used some existing VBA code and created new code, titled Module2_VBA_Script, that gives a more in depth analysis. We used various VBA functions in order to write this code, including: for loops, if-then statements, nested loops, visual formatting, and conditional formatting. We were also able to measure the performance of our code. 

Results/ Analysis:

Our dataset consists of 2 years of data of 12 different stocks, including "DQ," our clients interest. We created an Analysis of DQ and added buttons to make it easier for Steve to perform the analysis on his own. We also created an analysis of all 12 of the stocks we had data on, with a button on the worksheet for Steve to run the analysis. We then took this one step further; downloaded the starter code, renamed it, and began filling in the necessary data we needed to complete our analysis. First we created a tickerIndex and set it to 0. We then created the output arrays: tickerVolume, tickerstartingPrices, and tickerendingPrices; and assigned their data types. From there we began creating loops. The first loop we created was a for loop that allowed us to set tickerVolumes to 0. We then created another for loop that looped throughout the datset. The code provided color-blocked the cells, this makes it easier to see which stocks had over all gains or losses.

![colorblocking](https://user-images.githubusercontent.com/96501958/149700022-757bc8c7-4332-4576-92d6-1deea0073fe6.png)
We also made it so Steve can separate the data analysis from and few 2017 and 2018 separately, as well as together, depedning on his choosing. From our results we can see that all stocks, or "tickers," were up (had positive percent values)for 2017, except for TERP. 

![2017StockAnalysis](https://user-images.githubusercontent.com/96501958/149699805-48a6a93e-70d8-4b46-bf30-9e5012e972fd.png)
In 2018, however, only 2 tickers were had a positive return. DQ was up 199.4% in 2017, which was more than any other stock analyzed. It then dropped to -62.6%, leaving only ENPH and RUN with positive returnd for 2018. 

![2018StockAnalysis](https://user-images.githubusercontent.com/96501958/149699978-5773f17e-4b66-40fc-945e-431a47b343ca.png)

Summary

  Disadvantages:
  
Our code is limited to 2 years of data, making it hard to decipher if any of these stock are better than another. Even if we had more data to pull from and add to the dataset, it would require more effort than it is worth to write the code able to analyze thousands of different stocks, so we have to limit the options we would like to analyze. Because our code is so limited, we cannot draw too many trends from our results. We know that most of the stocks were down in 2018, but we do not know why and do not have enough data to see if it was just a bad year or if solar energy is on a decline that will continue for future years. 

  Advantages:
  
We are able to clearly deciper the various stocks and how they did both in 2017, 2018, and those 2 years combined. The code is also great for a smaller sized data set. If someone is stuck between a handful of stocks they would like to invest in, it is very helpful to see the year by year analysis and narrow down your options even further to pick a stock that is a safe investment and continuously goes up. 
  
