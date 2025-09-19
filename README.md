# daniw_altium_lib
Personal component library for Altium Designer

## Caution - Library update
On 2025-09-18, many components have been moved. 
This was done to have the origin in the center of the component, which allows to rotate many components through the properties panel. 

!!! IMPORTANT !!!
If you have used components from the library before 2025-09-18, these components are likely to move during an update from the library. 
Special care must be taken to avoid wrong connections. 

### Recommended procedure for an update from the library
It is recommended to follow this procedure for updating from the library: 
* Create a printout of the schematic as reference (PDF or on paper)
* update the PCB from the schematic (it might be necessary to perform multiple times)
* Note all changes from the ECO that cannot be resolved
* Update the schematic from the library
* Go through each schematic sheet and move any misplaced symbols back to its original location
* Remove shorts that were caused by the moved pins
* Compare the ECO list from a new PCB update with the list created in step 3 to find any remaining errors
