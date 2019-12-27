[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)

sample2 = np.random.random(1000)

pmf = thinkstats2.Pmf(sample2)
thinkplot.Pmf(pmf, linewidth = 0.25)
thinkplot.Config(xlabel='Random variate', ylabel='PMF')


cdf = thinkstats2.Cdf(sample2)
thinkplot.Cdf(cdf, linewidth = 0.25)
thinkplot.Config(xlabel='number', ylabel='CDF')

# Yes the distribution is uniform
