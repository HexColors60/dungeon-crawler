This project contains all necessary functionality. Grains are dropped
in the center of the map, then radiate out in the cardinal directions
when they become unstable. 

* `fillMapWithCommandLineValues` (line 40) handles command line arguments passed. 
* `dropSand` (line 53) drops sand in the center. 
* `handlePiles` (line 58) is what handles the toppling of piles. 
* `checkUnstable` (line 80) checks whether a simulation turn is ready to be ended or not. 
