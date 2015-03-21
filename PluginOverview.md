# Introduction #

This is a plugin for ImageJ which allows reading and writing HDF5 files. For a complete list of features see the [Features](#Features.md).
HDF5 is a data format for storing extremely large and complex data collections. For more information see the official website http://hdf.ncsa.uiuc.edu/HDF5/. The plugin uses the HDF5 Java Library for reading and writing HDF5 files.


## Features ##

  * Reading 2D/3D/4D datasets
  * Writing 2D/3D/4D datasets
  * TODO

## Requirements ##

  * ImageJ, plugins tested with Version 1.38 and newer.
  * Java, at least Version 1.5 (for HDF5 Java Library).

## Download and Install ##

  * TODO
Download the file to your ImageJ folder und unzip the archive. Delete all older versions before installing new ones, to be sure you have installed only one version at a time.

Since the the underlying HDF-Java library uses Java Native Interface you have to set the path to the native libraries. For example you are using linux 64bit OS (see README file in archive for other OS's), you have to edit the "run" file in your ImageJ installation directory that it looks like the following:

```
java -Djava.library.path=./lib/linux64 -Xmx512m -jar ij.jar 
```


## Current Stable ##

  * No current build. See [Older Releases](#Older_Releases.md) for the latest beta release

## Older Releases ##

[hdf5\_ij\_plugin.zip](http://lmb.informatik.uni-freiburg.de/people/schlacht/hdf5_ij_plugin.zip) (Old Version(beta) from 06.08.2010) --> [related instruction](http://lmb.informatik.uni-freiburg.de/resources/opensource/imagej_plugins/2010-08-06/hdf5_plugin.pdf)