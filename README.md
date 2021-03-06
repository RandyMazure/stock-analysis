# **VBA of Wall Street Challenge**

## Overview of Project
Steve, an aspiring Excel afficianato, was wanting to analyze the stock market in order to determine which stocks were performing the best.  An original macro was created to analyze 12 different stocks in years 2017 and 2018.  This macro had minor inefficiencies that were resolved with refactoring.   
## Results
The following are the return results of the 12 different stocks from 2017 and 2018 respectively:

![Year to Year](https://user-images.githubusercontent.com/100173822/161407829-d1b0a4ce-60b3-4288-bdbd-7c1ba9593bd7.png)

As can be seen, only two stocks had positive returns in 2018 (Tickers "ENPH" and "RUN").  Of those two stocks, "Run" was the only to increase returns from year 2017 to 2018.  
The second half involved refactoring code.  The following are the original run times for 2017 and 2018:

![INITIAL 2017 Time](https://user-images.githubusercontent.com/100173822/161407730-5eb4fcbd-8ea7-45ec-950c-10b91a2675c9.png)
![INITIAL 2018 Time](https://user-images.githubusercontent.com/100173822/161407731-0825d587-56a4-4410-9d57-0181ec6de3a7.png)

After making modifications to the tickerIndex variable, the run times were more efficient, albeit a small decrease:

![VBA_Challenge_2017](https://user-images.githubusercontent.com/100173822/161407782-0fa31e86-8c45-4f34-abc4-d1dac9bc0df1.png)
![VBA_Challenge_2018](https://user-images.githubusercontent.com/100173822/161407783-686d36c0-1550-4fa1-bbf5-f25bec76e896.png)

## Summary 
Refactoring code is a great way to make macro processes more efficient.  In this project, there were only 12 stocks that Steve wanted analyzed over two seperate years.  If Steve were to analyze more stocks, or more years, redundancies in processes would create longer run times and unncessary RAM usage.   

The major drawback to refactoring is the time it takes to first understand the original code, and then determine what code needs to be re-written in order to make processes more efficient.  The total time invested into refactoring may be more than the total time saved by refactoring.  

In this project, the new code was almost a carbon copy as the original with only slight modifications.  This made it easier to understand, however when working with other individuals, it may take longer to determine how they write code.  The code could also be longer and more confusing.  Refactoring in this project was only able to save a fraction of a second on the given data.  Not a worthwhile investment of time.
