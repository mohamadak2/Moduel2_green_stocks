# Moduel2_green_stocks

### Project Overview
  The idea of the project was that we needed to **diversify a client's stock porfolio**. The client decided to invest all their capital on the one DQ stock. We needed to be able to provide an analysis of certain other stocks to then difersify the client's portfolio. 
### available Data
We were able to obtain and analyze the following 12 stocks with their **Total Daily Volume**, and **Yearly return**.
- AY
- CSIQ
- DQ
- ENPH
- FSLR
- HASI
- JKS
- RUN
- SEDG
- SPWR
- TERP
- VSLR
----
## Results:
Here is an image that show the results for the 12 stocks in 2017 to 2018

![image](https://user-images.githubusercontent.com/47649575/131051093-385dad82-c595-4b41-89d3-59c8ca5b37c9.png)

As you can see that the DQ stock had a return of 199.4% in 2017! This is great and you would like to expect to purchase the stock in hopes of the of the climing return.
However, in 2018 the DQ stock had a -62.6% return. I believe that the stock is on the decline.

You can see that the stocks ENPH and RUN have a positive increase in 2018.


### Conclusion

I would not advise to allocate all your capital into DQ. I would consider to invest in the ENPH or RUN stocks.

### Limitations
I would love to have more data where we can analyze the fluctuation of these stocks over more yearly periods. This way we can see if DQ would have picked back up. Therefore you would purchase the stock at a lower price and see it's returns climb.


----
## Refactoring The VBA

The process of refactoring your VBA code is helpful to make your code run more effieciently. This way it will take less time to process.
After refactoring my code I was able to see a small improvement om efficiency.

#### Original VS Refactored Code

![image](https://user-images.githubusercontent.com/47649575/131052354-65cb38fe-cf76-4072-9b06-7ac543ae055a.png)

As you can see the Refactor code falls around 0.52343 seconds to run the analysis.
The original code takes around 0.59375

#### Conclusion

The benefits of refactoring my code allowed me to decrease the processing time by 0.07032 seconds. This may seem like a small difference however, if the data set was larger I believe the time difference would have been significantly larger.

However, the downside of refactoring the code was that it is time consuming and that we didn't need to in this case since the dataset was so small. The amount of time it takes to process the code does not justify the time to to refactor the code for such a small data set.

#### Final Thoughts
I believe every second counts. So the refactoring was worth it. Now I am able to increase the data set and have an effecient run time.
