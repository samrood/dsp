[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)

>> generate 1000 random numbers and plot the PMF:
rand = np.random.random(1000)
pmf = thinkstats2.Pmf(rand)
thinkplot.Pmf(pmf)
thinkplot.config(xlabel='Random Variable', ylabel='PMF')

>> what goes wrong?



>> plot the CDF:
cdf = thinkstats2.Cdf(rand)
thinkplot.Cdf(cdf)
thinkplot.config(xlabel='Random Variable', ylabel='CDF')


>> is it uniformaly distributed? 
>> Yes since it is relatively straight. 
