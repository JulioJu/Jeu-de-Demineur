# Minesweeper video game

## Overview

It's a small Minesweeper(video game), implemented for the class of [« Méthodes informatiques et techniques de programmation » (Université Grenoble 1)](https://dlst.ujf-grenoble.fr/?module=ue&idue=123).

***You can play with this video game, but it's not totally finished.***

See also relative [Wikipedia page](https://en.wikipedia.org/wiki/Minesweeper_%28video_game%29).

## @TODO

* Modular programming. 
* Import a clock. 
* Number counter of mines. 
* Change libraries, use the cross-platform development library [SDL](https://www.libsdl.org/).


## Installation

1. Compile graphsimple.c: `gcc -c graphsimple.c`
2. Compile graphlib_w2.c: `gcc -c graphlib_w2.c`
3. Links: `ar -r libgraph.a raphsimple.o graphlib_w2.o`
4. Make libary: `ranlib libgraph.a`
5. Step 5

* For root user :
        1. Put include files `*.h` in `/usr/include`, and put the libary in `/usr/lib`.
        2. Compile: `gcc Demineur.c -lgraphe -lX11`

* For not root user :
        1. Put include files `*.h` in custom direcotry, for example `/home/toto/include`. Put libary in a custom directory lib, for example `/home/toto/lib`.
        2. Compile: `gcc monprog.c -I/home/toto/include -L/home/toto/lib -lgraphe -lX11`

## Licenses

* The file Demineur.c, by juanes10 in under MIT license. 
* Libaries Graphsimple and Graphlib_w2 are under copyright, see this files for credits.

## Version 

Development started in november 2014. Last modified : december 2014. First realase : november 2015.
