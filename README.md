# StatisticalArbitrage

This project aimed to explore the concept of statistical arbitrage between two stocks. The CSV's exist as stock indexes in order to decide which ticket symbols to pull and how to filter them. 

The main jupyter notebook explores how using a rolling z-score pairs trading strategy can be exploited to find statistical innefiencies in the market. 

Effectively, if two stocks generally move together in terms of correlation, plotting their rolling z-scores as a ratio of each other can show us how they move in tandem. 

When one stock falls out of what would be considered a normal distribution (1.5 + standard deviations outside of a normal correlation ratio), we can make the assumption that it will revert.

This assumption is the underlying principle giving us buy or sell signals for trading. 
