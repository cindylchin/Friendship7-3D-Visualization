## Visualization Friendship-7 

I made a list of useful/not bad examples of real 3D visualization projects. I also tried to do a mockup of Friendship-7 project visualization. It's just a scheme of how it can be done, without any design yet. Just to start a discussion.

# Example 1

MAVEN (NASA’s Mars Atmosphere and Volatile Evolution mission)  

The special app shows orientation of the satellite as it points in different directions during its orbit, and the science data it collects from the Martian atmosphere and the solar wind.

Why I chose it: I think it’s a simple (from the point of view of visualization) example of using Cesium

![git1 mars](https://user-images.githubusercontent.com/26152025/35513894-29f854e2-050d-11e8-88c5-d21f3ec608fe.png)

Link to the Cesium application which displays MAVEN’s orbit: https://lasp.colorado.edu/maven/sdc/public/pages/maven3d/

Link to the project description on the Cesium site:  https://cesiumjs.org/demos/maven/


# Example 2

The Cube!

"The Cube Globe, an interactive visualization experience based on the Cesium WebGL globe engine. It was developed for the 2014 G20 Leader’s Summit in Brisbane, Australia, by the Visualization and eResearch (ViseR) group, located within the Institute for Future Environments at QUT, in partnership with the Queensland state government"

![git2 cube](https://user-images.githubusercontent.com/26152025/35513988-7d2ddd94-050d-11e8-860b-eafacec906e4.png)


"The Cube Globe uses data provided by the state to present stories using a range of data visualization techniques and an assortment of integrated media.


Through the use of spatial data visualization, animation, and touchscreen interaction, the globe encourages users to explore their place in the world via a novel, story-based interface. Stories are presented through key categories, and users can interact with statistical and spatial data while observing global connections"


Information about the project https://cesiumjs.org/demos/CubeGlobe/ 

Here is the video about the project: https://vimeo.com/112011647

# Example 3

Juno mission through NASA’s Eyes on the Solar System program

![git3 juno](https://user-images.githubusercontent.com/26152025/35514055-a50c7e2e-050d-11e8-82b7-aa3e76345290.png)

# Example 4

Satellites flight

I like it because of its simplicity.

![git4 satellites](https://user-images.githubusercontent.com/26152025/35514102-c37a0bec-050d-11e8-9ed8-ecd0092ffc66.png)

http://satellite.unisec.info/



## Friendship 7 visualization (let’s discuss?)

# F7 project description

The F7 project may be visualized using two parts or "screens".


The first one shows a 3D model of Glenn's flight. To animate the model we can use indicators, scroll bars, additional video/audio information. The second part describes how the team of the project has been working with data. 


There are different ways of how to visualize the project. It can be done in "ordinary" Cesium style or it can be designed using other tools. 


There is a mockup below (sorry, I'm not good at visualizing things, so it's just a scheme).


You can also find it through the link:  https://balsamiq.cloud/s2o4t/py6ku 


The first part

A user can see a model of the Earth, the starting point of the flight, and a model of Glenn's spacecraft.


The time bar at the bottom of the screen shows a horizontal scale with a marker. The position of the marker corresponds to the position of Glenn's spacecraft on the orbit.


Play/Stop and Forward/Back buttons are in the bottom left corner.


Checkpoints are particular points on the map/orbit line and correspond to events which happened during Glenn's flight. For example: switching from one tracking station to another, description of what Glenn saw and how he felt, etc.


Checkpoints are “active”. After the user clicks on it, a window with additional information appears.


To see how the flight looked like, the user can chose one of the following options. "Manual" (let's call it like that). It starts after the user chooses an icon in the upper right corner. After that, the user can rotate the model with the mouse, track different orbits, and chose specific checkpoints.


"Automatic". The flight begins after the Play button was pressed and it looks like a movie or a story. Then the user can see every event, which happened during the flight in every checkpoint, listen to dialogues, see photos, etc.

 

The Menu button is in the upper left corner. It can be displayed as a "hamburger" (triple bar) button or in any other way. The Menu can have subparagraphs with basic information:

-- About/History (Years of preparation)

-- Mission info

-- Spacecraft and instruments

-- Support from the ground (CapComs)

-- Glenn

-- Photo (?)

Note: This list is usually used by NASA when the Agency describes some project or mission.

![chechpoint zanzibar_medical information_with notes 1](https://user-images.githubusercontent.com/26152025/35514171-03cff2b0-050e-11e8-965c-29a4eb14acd3.png)


