# Stock Analysis
VBA Challenge on refactored stock analysis code

## Overview of Project
Steve's parents have invested into alternative energy by buying into the fund DAQO New Energy Corp. Rather than investing into this broad fund, Steve has asked us to take a closer look at the sector to find some more attractive options and to diversify. By using VBA, we have analyzed DAQO's performance along with other green energy stocks. 

### Purpose
We have refactored our code to run our stock analysis more efficiently in VBA.

## Results
Upon refactoring the code, we ran it for the 2017 year and then ran it again for the 2018 year. The refactored code ran for 0.0859375 seconds for the 2017 year compared to 0.6484375 with the original code. All stocks reported a positive return expect TERP which reported a negative yearly return of -7.2%.
![alt text](https://github.com/JoshTrewhella/stocks-analysis/blob/main/Resources/Refactored_2017.PNG)

The code refactored code ran for 0.0664062 seconds for the 2018 year compared to 0.6523438 with the original code. All stocks reported a negative return exceot for ENPH (81.9%) and RUN (84.0%). With the orginial code.
![alt text](https://github.com/JoshTrewhella/stocks-analysis/blob/main/Resources/Refactored_2018.PNG)

## Summary


### What are the advantages and disadvantages of refactoring code?
#### Advantages of Refactoring code?
By refactoring code this allows our code to run more efficiently. This lets us run our analysis faster, and in cases with longer and more complex code this could be significant. It also reduces the amount of computer resources needed to run our analysis. In cases of more complex code this could also save our company money, and will allow us to analyze larger sets of data.

#### Disadvantages of Refactoring code?
While refactoring code can have great end outcomes, the process of updating and rewriting code can present it's own challenges. The time and monetary commitment to rewriting already working code may not be worth the benefits. If the original code was written by a different coder, encountering errors could be troublesome and hard to debug if the original code is complex and not annotated properly. The refactored code's effectiveness is not always guaranteed to be worth the investment and maybe end up breaking the original code without a working solution. 

### How does these pros and cons apply to refactoring the original VBA script?
In this analysis, our refactoring of the code allowed the script to run faster than the original. For the 2017 data the time went from 0.6484375 to 0.0859375 and the 2018 analysis went from 0.6523438 to 0.0664062. Even though this may seem insignificant an improvement of ~10% can be significant in larger data sets. This shows our client that we are adding value to the process and allowing them to save time and money using our products. The cons of this refactoring is this improvement was not worth the time it took to refactor the code and the debugging process for the refactored code was more complicated than the original which already worked.
