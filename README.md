# the-basic
A quick refresher for basic computer science concepts and an excuse to get better at documentation.

This is not meant to be a guide however it may become useful refrence if I have done a good job.

The layout of this project is as follows.

	_______________________________________________________________________
	|                                                                     | 
	| projects/ ->                                                        |
	|          project/ ->                                                |
	|                   src/ ->                                           |
	|                         code                                        |
	|                   include/ ->                                       |
	|                         any headers                                 |
	|                   build/ - target dir for binaries                  |
	|                   Makefile - build instructions for this project    |
	| docs/ ->                                                            |
	|          docs generated by natural docs                             |
	|                                                                     |
	| scripts/ ->                                                         |
	|          build_tools.sh - source this file to have access to        |
	|          functions usefull for building each of these projects.     |
	| Dockerfile    - build enviroments syled as multi stage builds       |
    | Makefile.base - This is the base makefile that all projects can use |
	|                                                                     |
	|_____________________________________________________________________|

Documentation for this project is generated using [Natural Docs](https://naturaldocs.org/) 
and is published via [GitHub Pages](https://pages.github.com/) [here](https://superxkooda.github.io/the-basics)