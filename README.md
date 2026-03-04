
# Simultaneous Localization and Mapping Using Fiducial Markers
[![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](LICENSE)

## Overview

This package implements a system that uses ceiling mounted
fiducial markers (think QR Codes) to allow a robot to identify
its location and orientation.  It does this by constructing
a map of the ceiling fiducials.  The position of one fiducial
needs to be specified, then a map of the fiducials is built 
up from observing pairs of markers in the same image. 
Once the map has been constructed, the robot can identify
its location by locating itself relative to one or more 
ceiling fiducials.

Documentation is at [http://wiki.ros.org/fiducials](http://wiki.ros.org/fiducials).

Demo-video is at [Google drive](https://drive.google.com/drive/u/3/folders/16AtCFrNIujAwx2jWts5mgv8NM7F2jYix).
