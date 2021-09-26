# Stock Market VBA Project and Refactoring
---
## Background:
The goal of our work on this project was to provide a systemic and repeatable way to pull data in common formats about the stock market across a number of specific stocks.  For this type of analysis the volume traded of the various items, the beginning and ending prices with a calculated return are the bare essentials.  We’ve provided some easy to read color coding as well to identify those items with a positive and negative return.
---
## Results:
2017 was a banner year for the stocks that we evaluated.  The portfolio overall had a 67.3% return with individual returns ranging from -7% to almost 200%.  We managed to get the code to refresh this data to execute in about 2.1 seconds.

![2017 Results](https://github.com/madrivers/VBA-Challenge/blob/main/Resources/2017%20Returns.png)
---
![2017 Runtime](https://github.com/madrivers/VBA-Challenge/blob/main/Resources/2017%20Run%20Time.png)

2018 was a more difficult year for these stocks.  Overall the portfolio had a return of 102% with the only two stocks with positive returns being ENPH and RUN, returning 82% and 84% respectively.  All others negative returns ranged from -3% to -63%.

![2018 Results](https://github.com/madrivers/VBA-Challenge/blob/main/Resources/2018%20Returns.png)
---
![2018 Runtime](https://github.com/madrivers/VBA-Challenge/blob/main/Resources/2018%20Run%20Time.png)

With the caveat that prior results do not guarantee future performance, ENPH and RUN would have been nice additions to any portfolio.

## Summary:
With the caveat that prior results do not guarantee future performance, ENPH and RUN would have been nice additions to any portfolio.
The refactored code yielded varying results – reducing the run time of 2017 by .5 seconds while leaving the 2018 runtime relatively unchanged.
The Pros of refactoring code are of course the continued evolution of the code for updates and efficiency, the incorporation of new elements and the programmer learns new ways of doing things.  

When refactoring someone else’s code a clear CON has to be the ability to understand the original intent, the layout and approach.  Another potential disadvantage of refactoring code is taking something that is working well, and due to error or oversight make it no longer work.  This requires additional time in debugging.  A clear mindset for good enough should be employed to balance the cost (time) vs. benefit of continuous refactoring.


