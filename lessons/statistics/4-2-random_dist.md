[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)

>> 
A: Yes the graph of both cdf and pmf shows that the distribution in uniform.

import numpy as np

rand = np.random.random(1000)

cdf = thinkstats2.Cdf(rand)

pmf = thinkstats2.Pmf(rand)

thinkplot.cdf(cdf)

thinkplot.pmf(pmf)
