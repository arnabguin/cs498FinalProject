# cs498FinalProject
d3 narrative visualization



MESSAGING:

The car buying guide offers options to explore alternatives when a potential buyer on the market wants to make a decision 
on which vehicle to buy based on certain criteria.

NARRATIVE STRUCTURE:

The structure used in this visualization is a Drill-down story. There are primarily 3 scenes in the slide show and each allows
the user to drill-down into additional details.

VISUAL STRUCTURE:

Connection between scenes is achieved through a tabbed menu at the top of the page. The user needs to click the hyperlink 
on each of the scenes in order to view data corresponding to a scene. 

Bar charts: Tooltips are used to aid the user in seeing the property value (city mpg) corresponding to a vehicle make. Also, 
in the engine cylinder bar chart, size of each dot is used to proportionally indicate number of engine cylinders.
Scatter plots: Users can zoom in (through d3 brush) on a section of the scatter plot
Tables: Users can sort data by property type (make, cylinders, mpg etc.)

SCENES:

Scene1: Explore vehicle makes and models 
     Drilldowns: 3 bar charts describing 3 characteristics (engine cylinders, city mpg, highway mpg) for each make of vehicle
Scene2: Run analytics
     Drilldowns: Zoomable scatter plot showing correlation between city and highway mpg
Scene3: Make a decision
     Drilldowns: Sortable table data with highlighting so user can sort vehicle data by 5 different fields
     
ANNOTATIONS:

Tooltips and size of circles are used to aid the user in visualization. Also, there are text annotations used in 
all scenes to denote next steps user needs to take in the decision making process

PARAMETERS:

SVG dimensions, axis domains and ranges, color schemes, width of bars in bar chart, width and color of bubbles in bar charts
Font and color of scenes
These paramters either remain constant or change from scene to scene.

TRIGGERS:

Sort drop-down: User can sort data by a property in a menu dropdown
Zoom: Users can zoom into data in scatter plot by dragging out the mouse
Hover: On hovering over the bubbles in a bar chart, size of bubble increases during the hover and it goes back to original size 
once the user moves the mouse away.

Affordance is provided through annotation texts that the user can easily notice when visiting the scene. 
