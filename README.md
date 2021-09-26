# urc_2022_aruco_markers
This package contains the aruco 4x4_50 library tags that will be used in the 2022 edition of the University Rover Challenge (ID 0 to 5). The tags have been formatted according to the rule book. 

The tags measure 15 cm in width with an added white border of 1 cell which brings the marker to a total of 20 cm. 

The tags are available as SVG, PNG and Gazebo models to use in a simulation.

## How the models were made
The Gazebo models were made by using SolidWorks to make the triangular prism and blender to apply the tags on the three faces. The blender project files and the prism STL is available under `blender`

## Usage
If you are using this with ROS, the Gazebo models should automatically be exported to the gazebo models path, meaning they can be imported in the simulation just like any other default model.

## Credits
The tags were generated using this tool: https://chev.me/arucogen/
