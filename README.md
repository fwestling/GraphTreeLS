# GraphTreeLS
A set of scripts which can be used to perform "graph operations" on point clouds of trees
Specifically, the operations are: 

* Trunk classification
* Individual tree segmentation
* Locate trunks 
* Simulate pruning at a given cut point

Most scripts are implemented in Bash, relying heavily on the ACFR Comma and Snark libraries (https://github.com/acfr/comma and https://github.com/acfr/snark).
An install script is included which should install all requirements, though may not work on recent versions of Linux; it has been tested on WSL2 with Ubuntu 18.04.
A Docker script is also included, but has not been tested in this exact configuration.

The main function involved is "graph-op" ; for this and all scripts included, if you run it with the command line argument `-h` (e.g. `graph-op -h`), you will be given descriptions and a list of operating parameters.

The input data expected is Comma-generated binary pointcloud files.

The scripts included here are a subset of a larger project and have not been isolation tested, so please contact us if you encounter any missing script errors.
