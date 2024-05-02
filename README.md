# Stable Tree Labelling

A tool to speed up distance queries for dynamic road networks, 
It consists of the following main files:

* road_network.h / road_network.cpp: core library
* util.h / util.cpp: library with additional tools

Additional files are:

* index.cpp: create an index file
* query.cpp: load index from a file and evaluate random queries
* update.cpp: update index to reflect graph changes
