# Vacuum_Cleaner_AI_Robot


Introduction:
The goal in this project is to practice design and implementation of
the common search algorithms for intelligent agents in a static fully
observable grid environment. This project is provided in the form of a
shell module, and you are going to add or modify it to fulfill the
requirements. The parts that you will need to implement have printout
comments saying "Your code goes here" or such. Once you have done a part,
comment out the print function using #.
The code base distributed is a shell with all the mechanics been
implemented. The code contains lots of comments and instructions. Read
them carefully.
The environment is a 2D grid of rooms among which some are set to
'dirty'(grey color). There is a collection of blocked rooms as well. The
blocked rooms and the boundary walls are red colored. There is a vacuum
cleaning agent which moves from room to room and cleans them. The agent
has a location and direction that is heading. The default cost of moving
from room to room is 1.

Tasks:
The goal is to use various search algorithms to help the robot to go
around efficiently and clean rooms, as intelligently as possible.
You are going to implement 5 search algorithms: BF Graph, DF Graph, UCS,
Greedy, and A*. The tasks are basically to complete and implement all the
algorithms using the framework provided.

The way search will work is that the path node and the explore list are
computed when one selects a search algorithm from the menu. The explored
list of nodes is immediately displayed using pink color. Using the ‘next'
or 'run' buttons one can step through the path from the current agent
location to the selected goal which is a dirty room. For 'run' the steps
follow one another automatically. The app displays 2 counters at the top,
keeps track of the total number of explored rooms and the number of rooms
on path as the agent progresses through the grid automatically.


Commandline Arguments:
The agent can be launched from command line as following:
>python VacuumSearch.py -s searchType -c costFunction -r heuristic -n
(corners)

