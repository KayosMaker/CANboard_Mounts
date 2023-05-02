# Mounting Solutions for Nema 14 Based CANbus Toolhead Boards
Files are available to support the following boards:
* BTT EBB36 CAN v1.0
* BTT EBB36 CAN v1.1
* BTT EBB36 CAN v1.2
* Mellow FLY SHT-36
* Mellow FLY SHT-36 2.0


## Extruder Compatibility
Since each popular extruder using a NEMA 14 motor seems to use it's own unique motor orientation, I created this set of mounts to cover most common setups.  These mounts allow the board to be oriented properly with the umbilical strain relief pointing up, despite the different motor orientations.  I have found 5 different motor angles among common NEMA 14 extruders in open source 3D printing.  If there's a common extruder with a different motor orientation that I missed, just message me on Discord or open an issue here on Git.  The current files align with the motor orientation of the following extruders: 
* Sherpa Mini
* LGX Lite
* Sailfin (OG Sailfin as well as my silly Sharkfin mod)
* Orbiter v1.5
* Orbiter v2.0.  
![](images/extruders.png)

## Plate Types
There are 3 types of plates available: plain, strain relief, and overmold strain relief.  Each has a dedicated folder for the related stls.  The basic strain relief is for most diy cables.  The overmold strain relief is for retail cables available from Molex.  The plain brackets are for printers that have their own solution for umbilical or cable chains. 

Mellow has moved to a new dual plug setup on the FLY SHT-36 2.0, negating the use of the overmold brackets.  Stick with the regular strain relief versions for that board.


![](images/ebb36_full_lineup.png)
![](images/sht36_full_lineup.png)


## Usage Notes
The output for the stepper can be switched to the other side of the board if the user wants it so.  The bracket base geometries have clearance for that in regular and mirrored orientations.  Not all extruder motor orientations allow this, but some do.
![](images/sht36_stepper_plug_orientations.png)

These plates are meant to work with printed mounting posts as spacers.  The extruder motor gets mounted with screws that are 5mm longer than called for(so they protrude from the back of the motor mounting ears).  Each end of the printed standoff post gets an M3 heatset insert.  Mounting post length should be chosen based on the motor you are using.  Measure the distance from the back of the motor to the back side of the mounting ears.  Add .5-1mm so the board mount isnt touching the motor, and print the corresponding post length from the folder.  The post is screwed onto the protruding motor mounting screw, and then the mounting bracket is screwed into the mounting posts.  Then you mount the board on the bracket.  The brackets with different board and motor screw orientations will require heatsets in the bracket, to mount the board. 

There are 3 styles of standoff posts available.  They print in the orientation shown.  The classic round ones are fine as long as you print hot enough that layer adhesion is strong.  Geometry is in place to allow the internal overhang to print easily.  If that makes you uneasy, choose the octagonal or teardrop shapes and print them lying down as shown.  
![](images/mounting_post_types.png)


## Usermods
Mod|Description|Link
|:--------:|:-------------------------:|:---:|
Reapola's Galileo Mounts|Mounts for rear or side of Galileo, with CAD|https://github.com/KayosMaker/CANboard_Mounts/tree/main/Usermods/Reapola/Galileo%20Mount%20for%20SHT36
