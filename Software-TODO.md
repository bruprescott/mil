
        Exploring: 
	[] If we see no objects, move in some way
	[] If we see multiple objects, pick the closest object, LOOK AT IT, tell the OC to begin classification, move towards it.

	ROS SERVICE:
		[] Turn off turn 


        OD:
	[X] Put GPS BB points as rosparams
	[] OD only gives you objects that are far from the objects that you have already seen, and updates the positions of the old objects

	[X] ROS Topics: List of objects, Marker 


        OC:

	[] Buoy Field, Tower Buoys, Dock, STC, Shooter, Unknown

	[] ROS Topics: 
		[] Publishes name of object when it is found	
		[] Publishes Marker Array of text for visualization

	[] ROS Services:
		[] 	Query to database

	[] Do not add to launch file for now
	RULES:
		- take human input, lol this will work

        Mission System:
	[] Add to launch file