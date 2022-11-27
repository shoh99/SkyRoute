# Vancouver public metro system

I tried to create Vancouver's public metro System, to help commuters get from one landmark to another. This program is called `SkyRoute`, a routing tool that uses *breadth-first search*(bfs), *depth-first search* (dfs) and Python dictionaries to accomplish this feet. 

## Files of this project

* *graph_search.py* has the `bfs()` and `dfs()` functions implemented in Python
* *vc_metro.py* contains a graph of all stations in the Vancouver metro system.
* *vc_landmarks.py* contains a dictionary of Vancouver landmarks mapped to their nearest metro stations(s)
* *landmakr_choices.py* contains a dictionary of letters of the alphabet mapped to landmarks to make it easier for users to make a selection.
* *skyroute.py* is main file, where all files are imported and main functions are build.
