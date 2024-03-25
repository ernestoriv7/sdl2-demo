# Demo

This a demo of a moving object in a screen that has collision with another
element.

This is intended for the students of DSD with professor Ernesto Rivera.

After installing SDL2 on Linux, the compile command is the following

	gcc demo.c `sdl2-config --cflags --libs` -o demo

The included Makefile works for depeloping on MacOS. It can be modified
to compile for Linux.

SDL initialization, the numbers map and some routines are taken from:
https://github.com/flightcrank/pong

Several comments in the source file are added to appoint specific factors
and improve programming practices.

After starting the first screen press space bar.

