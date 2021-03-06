# mLibTerrain

A Library of Procedural Displacement Surface Operators for Sidefx HoudiniFX. 
Currently in Beta Version. 

- https://github.com/Doudini/mLibTerrain
- https://www.facebook.com/microbot23


#### About

mLibTerrain is a digital asset library for Sidefx Houdini.
It Contains a Set of Artist Friendly Tools to generate Displacement Maps. 


#### Content
- /otls		- Houdini Digital Assets
- /otls/base	- Base Digital Assets
- /otls/exp	- Unfinished Experimental HDA's
- /otls/grave	- Old Assets
- /gallery	- Set of Galleries for each SOP containing several predefined Settings.
- /examples	- Some Examples
- INSTALL	- Installation Instruction
- LICENSE	- Artist License


#### Tools

- Displacer		- Just a simple VOP to displace based on CD attribute
- Fractal Noise		- Creates a Fractal Noise
- FractalWithShaper	- Creates Fractal Noise with an additional Shaper Option
- TerrainCometizer01	- Let's you create Comet and Asteroid Impacts
- TerrainCometizer02 	- Let's you create Comet and Asteroid Impacts
- Radial Gradient	- Simple Artist Friendly Gradients
- Unified Fractal	- A Unified Fractal Noise Version.


### Quick Installation

- Download the latest dev-branch (see link above)
- Extract and move it into your Houdini config directory
- Append the provided houdini.env example file to your own houdini.env


### Installation

The installation process involves two steps: **getting the contents** and
**setting up the environment** for Houdini.
Please Check the attached INSTALL text file for a Detailed Installation. 

#### 1. Getting the contents

You can either grab a compressed archive file (as mentioned above), or
you can clone the official repository with **git**.

The archive way is the easiest, but using git has additional benefits,
such as instant updates, easy access to older versions, other development
branches, etc.

#### 2. Adding it to the Houdini environment

The easiest way to do is to customize your
<a href="http://www.sidefx.com/docs/current/basics/config_env">houdini.env</a>


### Submit Bugs/Contact:
I appreciate bug reports, RFEs (Request For Enhancement), or feedback of
any kind. Feel free to contact me at mLib@microbot.ch


### qLib:
Please also have a look at the famous qLib for Houdini at https://github.com/qLab/qLib
It contains a lot of awesome Tools. Thanks to them I could make this Readme. ;)
