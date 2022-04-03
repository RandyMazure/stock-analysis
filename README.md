# **VBA of Wall Street Challenge**

## Overview of Project
Steve, an aspiring Excel afficianato, was wanting to analyze the stock market in order to determine which stocks were performing the best.  In addition, Steve was wanting a more efficient way to go through the code for future purpose to run more stocks. 
## Results
The following are the results from 2017 and 2018 respectively:

![Year to Year](https://user-images.githubusercontent.com/100173822/161407829-d1b0a4ce-60b3-4288-bdbd-7c1ba9593bd7.png)

As can be seen, only two stocks had positive returns in 2018 (Tickers "ENPH" and "RUN").  Of those two stocks, "Run" was the only to increase returns from year 2017 to 2018.  
The second half was to refactor code.  The following are the original run times for 2017 and 2018:

![INITIAL 2017 Time](https://user-images.githubusercontent.com/100173822/161407730-5eb4fcbd-8ea7-45ec-950c-10b91a2675c9.png)
![INITIAL 2018 Time](https://user-images.githubusercontent.com/100173822/161407731-0825d587-56a4-4410-9d57-0181ec6de3a7.png)

After making slight modifications to the code, the run times were able to decrease, albeit a small decrease:

![VBA_Challenge_2017](https://user-images.githubusercontent.com/100173822/161407782-0fa31e86-8c45-4f34-abc4-d1dac9bc0df1.png)
![VBA_Challenge_2018](https://user-images.githubusercontent.com/100173822/161407783-686d36c0-1550-4fa1-bbf5-f25bec76e896.png)

## Summary 
Refactoring code is a great way to make macro processes more efficient.  In this project, there were only 12 stocks that Steve wanted analyzed over two seperate years. This equivalated to 3,012 line items in the original Excel document.  If Steve were to analyze more stocks, or more years, redundancies in processes would create longer run times and unncessary RAM usage.   

There major drawback to refactoring is that it takes time to first understand the original code, and then more time to determine what code needed to be re-written in order to make processes more efficient.  This time invested in refactoring can be more than the time the refactoring saves.  

In this project, the new code was almost a carbon copy as the original with a only a few steps missing.  This made it easier to understand, however when working with other individuals, it may take longer to determine how they write code.  Refactoring in this project was only able to save a fraction of a second, but this is due to the limited data.  
