# LiveLessful Analytics

In my Sophomore year, I worked in a team of 5 to build a digital brand as a joint Marketing/IT class project.
My main task was to work with the twitter content creator to collect, analyze, and generate insights from the data that Twitter let us export.

These visualizations were either part of Exploratory Data Analysis, or used in our final presentation where I described our reach maximization strategy and content insights we could use in the future.

To learn more about my work on this project, check out my [Medium write-up](https://medium.com/@learley1/applying-bayesian-optimization-in-unconventional-settings-d940af863965), or email me at learley1@babson.edu!

![Gaussian Process Visualization for Metrics](https://github.com/Liam-E2/VisualizationRepo/blob/master/LiveLessful/GPTwitter.png)

I wanted to implement a sort of Bayesian Optimization-based process to maximize our impressions based on time posted, but had two main issues: I didn't have the time to implement expected improvement, and even if I did I needed to communicate effectively it to my non-technical team and class. I opted to create visualizations of the Gaussian Process model, which showed uncertainty (the blue shaded area) and observed performance (the blue through-line). Good areas of the graph to explore (by posting during that hour) are areas where uncertainty is high, to gather more information about expected performance, and where expected performance is high, to maximize the desired metric.

Also check out a smoothed version of this graph thatillustrates the trend better, but is less useful for the iterative process due to the effect on uncertainty regions:

![](https://github.com/Liam-E2/VisualizationRepo/blob/master/LiveLessful/Gauss2.png)
