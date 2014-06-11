catkin_wtf
==========

Simple tool to add a package dependency to the 4 locations in a catkin package

## Usage

```
roscd YOUR_PACKAGE_TO_MODIFY
python ../path/to/catkin_wtf.py <dep_name>
```

:-)

## Current Limitations

 - You don't mind formatting of your package.xml being messed up.
 - You don't mind the deps being added to the bottom of package.xml
 - 'find_package(catkin REQUIRED COMPONENTS' is on the same line
 - You can only pass in 1 dep at a time

These are all pretty easy to fix, I just should be working on something else right now


