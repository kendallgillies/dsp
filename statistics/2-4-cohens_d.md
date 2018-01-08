[Think Stats Chapter 2 Exercise 4](http://greenteapress.com/thinkstats2/html/thinkstats2003.html#toc24) (Cohen's d)

>> Python Code:
>>
>> ```python
>> def CohenEffectSize(group1, group2):
>> 	diff = group1.mean() - group2.mean()
>> 	var1 = group1.var()
>> 	var2 = group2.var()
>> 	n1,n2 = len(group1),len(group2)
>> 	pooled_var = (n1*var1+n2*var2)/(n1+n2)
>> 	d = diff/(pooled_var)**(1/2)
>> 	return d
>> 	
>> CohenEffectSize(firsts.totalwgt_lb,others.totalwgt_lb) 
>> ```
>>
>> Answer: 
>>
>> ```python
>> -0.088672927072602
>> ```
>>
>> The first babies are on average smaller than the other babies by approximately 0.124 lbs, which seems contradictory to the fact that the pregnancy length for first babies is on average longer than the pregnancy length of the other babies.  However; the Cohen’s d statistic is only -0.089 which is too small to draw any conclusions from, i.e. not statistically significant.

