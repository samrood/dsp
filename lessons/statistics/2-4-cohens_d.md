[Think Stats Chapter 2 Exercise 4](http://greenteapress.com/thinkstats2/html/thinkstats2003.html#toc24) (Cohen's d)

>> mean of baby weights: 
firsts.totalwgt_lb.mean(), others.totalwgt_lb.mean()
(7.20109, 7.32585)
Shows that first babies are lighter than others 

Cohen's d for difference between groups:
CohenEffectSize(first.totalwgt_lb, others.totalwgt_lb)
(-0.08867)

Cohen's d for difference in pregnancy length:
CohenEffectSize(firsts.prglngth, others.prglngth)
(0.028879)
The chonen effect for the difference in pregnancy length is much stronger than the effect for the difference in total weight 
