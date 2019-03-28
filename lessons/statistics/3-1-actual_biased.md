[Think SREPLACEtats Chapter 3 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2004.html#toc31) (actual vs. biased)

>>  

resp = nsfg.ReadFemResp()

respo = resp.numkdhh

resp1 = thinkstats2.Pmf(respo, label='actual')


biased_resp1 = biasresp1(resp1, label = 'observed')
thinkplot.PrePlot(2)
thinkplot.Pmfs([resp1, biased_resp1])
thinkplot.Show(xlabel='number of children', ylabel = 'pmf')
print(resp1.Mean())
print(biased_resp1.Mean())


mean = 1.024205155043831
mean = 2.403679100664282
