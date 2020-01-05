[Think Stats Chapter 3 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2004.html#toc31) (actual vs. biased)

>> actual distribution for the number of children under 18 in the respondents' households:
>> resp = nsfg.ReadFemResp()
>> pmf = thinkstats2.Pmf(resp.numkdhh, label='numkdhh')
>> thinkplot.Pmf(pmf)
>>thinkplot.Config(xlabel='Number of Children', ylabel='PMF')

>> biased distribution of children under 18 (including themselves) in their household:
>> biased = BiasPmf(pmf, label='Biased')
>> thinkplot.PrePlot(2)
>> thinkplot.Pmfs([pmf, biased])
>> thinkplot.Config(xlabel='Number of Children', ylabel='PMF')


>> means of the two:
>> pmf.mean() = 1.0242
>> biased.mean() = 2.4036
