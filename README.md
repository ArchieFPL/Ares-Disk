# Ares-Disk
![ares-disk](https://pbs.twimg.com/media/EiH_syRXcAUpn9H?format=jpg&name=large)
## Introduction
Ares-Disk is an interactive TUI S.M.A.R.T viewer for Unix systems.

## Features
* UI similar to CrystalDiskInfo.
* Health and temperature checking algorithms based on CrystalDiskInfo.

## Required libraries
* ncurses
* libatsmart

#### Debian(or derivative) Systems
```
# apt-get install libatasmart-dev libncurses5-dev libncursesw5-dev
```

## Build and Run
```
$ mkdir build
$ cd build
$ cmake ..
$ make && make install
```



![]()
