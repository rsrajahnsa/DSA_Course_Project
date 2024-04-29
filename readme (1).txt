----> Shortest Path Finder with Traffic Simulation  <----------

Overview:-
This C program simulates a scenario where you need to find the shortest path from your current location to the nearest electric vehicle (EV) charging stations. It takes into account traffic conditions and road closures to provide accurate distance estimations.

Features:-

Uses Dijkstra's algorithm to find the shortest path.
Considers traffic conditions (low, medium, high).
Handles road closures appropriately.
Simulates traffic updates every 5 seconds. 
Supports multiple EV charging stations.
Outputs the nearest EV station, distance, path, and traffic condition.


-------->
Usage:-
Compilation: Compile the program using a C compiler such as GCC


-------->
Output: The program outputs the nearest EV station, its distance, path, and traffic condition from your current location. It simulates traffic updates every 5 seconds for a total of 25 seconds.

-------->
Dependencies : -
Standard C libraries: stdio.h, stdlib.h, stdbool.h, limits.h, time.h, unistd.h

--------->
Configuration : -
Modify NUM_VERTICES to adjust the number of locations in the graph.
Update the addEdge function calls to define the graph structure according to your scenario.
Adjust the ev_stations array to specify the locations of EV charging stations.
Customize the number of iterations and sleep duration in the main function loop.

---------->

Author
(Aditya , Rohan , Rutam )