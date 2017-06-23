# Jydgets

# Bidirectional jupyter widgets for neuroimaging and statistical analyses 

Brainhack Vancouver 2017, Katja Heuer & Roberto Toro

This project aims at creating bidirectional jupyter widgets for neuroimaging, bringing your results into a 2D or 3D interactive canvas, and being able to communicate selected data back to your code.  

### Motivation  
The incorporation of interactive (2D and) 3D data visualisation into neuroscientific research process and reports not only facilitates intuitive understanding among the original researchers but also makes it easier to share data and insights with others. Jupyter notebooks provide a perfect environment for the scientific community to share their analyses in an easily reproducible way and present results integrated within the workflow. However, figures often represent only a snapshot of the data, and in the (rare) cases where they are interactive, they react to your input but would not provide selected data back to you for integration into your workflow.  

### Aims of the project  
We want to build a set of user-friendly widgets that will be bidirectional:  they will display your data, and feed your interactions back to the python code. During Brainhack we want to prototype bidirectional widgets for interacting with stereotaxic and surface data, as well as with data visualisation libraries such as d3. In the longer term, we could together work to establish a standard set of tools and best practices for interactive 2D and 3D neuroimaging and statistical data. 
In more detail these widgets could be 
	•	A stereotaxic viewer able to display brain slices and feed back to your code the selected plane, slice and cursor position,
	•	a surface viewer widget able to display 3D surfaces (using three.js) and feed back to your code the point where you click,
	•	a d3 widget able to represent your network data and feed back to your code the index of a selected node,
	•	BrainBox and Brainspell widgets able to display and recover data from their respective websites,
	•	a BrainGL-Web widget able to display interactive 2D figures and connectivity diagrams connected to a 3D viewer ready for inclusion in your online publication 
The widgets will be released open source on GitHub, and their javascript code will be injected on-the-fly into your jupyter notebook, without requiring any additional package installation. Our project will facilitate data exploration, as well as the sharing of analysis methods and results, improving research reproducibility.
  


#### Collaboration  

We will be super happy to work with anyone who would love to join our effort.  
Join us! :)  
 
 
 
#### Curious?  

BrainBox and Brainspell, for instance, can be here 
[BrainBox](http/://brainbox.pasteur.fr)
[Brainspell](http://brainspell.org)
 
 
#### Join us!  

Join our project on github any time :) and join us also for Brainhack Vancouver!
or on our [slack channel](https://brainhack-slack-invite.herokuapp.com/) #jydgets. 
 
 

**We are looking forward to meeting you! :)**  


