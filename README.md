# H517Project1
Project 1 for my H517 Data Visualization class at IUPUI
http://vis.ninja/teaching/2018/H517/project1/

TODO:
Document the following on the ABOUT page:
	Your design process: How did you go about designing the visualization? What are some of the initial designs / ideas you attempted in the beginning? A good way to document your design process is to scan your sketches and include them in the documentation page.
		Iterative design: Draw map, draw graph, make graph interactive by date, add gender data, add age data
		Estimated placement of building and street labels.
		User testing
		Tried to use scale bands for the hover bars but it wouldn't center them correctly.
		Tried to use diverging colors for age chart but middle colors didn't contrast enough with white background.
	Rationale of your design choices: This should be a rigorous explanation of the design choices you made. For example, why did you use color to encode a particular variable? Why did you arrange your charts in a particular way?
	Describe how you used your visualizations to discover facts or answer questions you had. Include evidence to support your findings as screenshots from the visualization. In this case, we have a clear hypothesis to start with, but are there other nuggets of insights one can uncover?

A 2-4 minutes YouTube video showing the use of your visualization with narration. This video should be embedded in your documentation page. The video should be created using a screen-capture tool while interacting with the visualization. It should ideally be similar in style to the videos that accompany papers at the IEEE VIS or ACM CHI conferences. Here are a couple of good examples: UpSet, and GPLOM

Upload the application to my website.

IF THERE IS TIME
Change the Y scale for the different modes.
Add dotted line with baseline death rates for comparison.
It would be nice if, below a certain width, the graph dropped below the map.

FOR AN A YOU NEED TO ADD:
	ability to zoom in/out and pan around the map
		https://github.com/d3/d3-zoom

	ability to cluster the data on the map into a grid that shows the number of dead in each grid cell (even with this small amount of data the points are starting to overwhelm) and the user should be able to vary the size of the clusters.
		https://www.phase2technology.com/blog/using-d3-quadtrees-power-interactive-map-bonnier-corporation

	ability to show data from a window of days on the timeline graph

