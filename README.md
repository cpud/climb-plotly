# climb-plotly

Open the 'Final' notebook and run all cells to see the end visual. It may take a couple minutes to gather all of the data.

mtnprojDF is a csv file that is the final dataframe used for the visual.  

Using data scraped from Mountain Project, a website where users share rock climbing routes,
I created a plotly choropleth map that show which states have the most routes, while also displaying the amount
of certain types of routes (toprope, boulder, etc) and the number of Crags (climbing areas). Note that Nebraska and 
Mississippi don't have any data because they are very flat states. 

The 'messy' folder contains various unorganized scratchwork and should not be viewed if you value organization. 

This is my first foray into gathering my own data, and also my first side project. Web scraping is very messy!
From the start, I have been aware of the inherent flaws of this project.  Many climbing areas are secretive and exclusive,
and won't be shared with the public, let alone posted on Mountain Project.  I personally know of a couple crags near where I live
that aren't on Mountain Project, and I'm certainly no 'insider'.  

Furthermore, if you compare the displayed Total number of climbs with the sum of the individual types of climbs, you may find
that these amounts don't match.  This is because some routes are considered both Trad and Toprope, so they get counted twice.  

Overall, this project was meant to get me familiar with gathering and cleaning my own data, while creating something that is 
interesting to look at, even if it is not 100% accurate to reality.  The biggest surprise is Massachusetts having the most crags,
at 110, while California only has 19.  California definitely has more than 19 areas, and most of the MA crags have less than 100
routes, while each CA area is upwards 250, with Joshua Tree alone having 6000 posted routes while all of MA only has 4000. Again,
it is important note that these are merely the routes shared on the internet. My go-to crag is listed at under 300 routes,
but if you ask the climbers who have been going there for years, they could show you over 1000 routes. 
