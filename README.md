
Affordable high temperature filament 3D printer

We are working toward an affordable 3D printer capable of printing high temperature engineering filaments. Current printers capable of turning out reliable parts from PEKK, PSU, etc. cost several thousand USD; but I think we can do better for cheaper.
The project has been started by the DEFCON 404 security enthusiast group, and is being discussed on their discord server.  The project is open to all interested parties with something to contribute!


The Dream
3D printers capable of turning out usable parts from PEKK, PEEK, or PEI typically start around $7000 USD, so we are trying to design and build the first "affordable" printer to do it. (PEEK cost ~$500USD/1kg for perspective on affordable)

When can I play too?
Before releasing plans, manuals, etc. this stuff must exist, so we are planning to create all that stuff AFTER producing a working, tested, & reproducible system that does the thing.


## Hardware
In this section we will discuss what hardware sections we will need to create
- Extruder
- 	Which Off-The-Shelf extruder product?
- 	Which Hot-End product do we want?
- 	Remote or direct drive?
- 		No Bowden, too much flex
- 		Remote drive (think weed eater cable drive)
- 			Would have some added backlash due to flexing
- 		Direct Drive
- 			Requires liquid cooling blocks for each side of the extruder stepper with 2 silicone tubes runnning with the wires to the hot-end
- Kinematics
- 	Ball screws moving linnear rails
- 		Need reducing transmission of some type
- 			No Backlash REQUIRED
- Build Plate
- 	1/4" minimum thickness Glass sheet
- 	1/8" minimum thickness Carbon Fiber sheet
- 	3/16" minimum thickness FR-4 (Circuit Board) sheet
- 	Which Off-The-Shelf Heated Bed are we going to use?
- 		Requires 150c temperature with 100% duty cycle
- 	How are we retaining the Build Surface?
- 		Temperatures too high for magnetic build plates
- Frame
- 	20x20 standard aluminum rails with various hardware


## Software
This section will be where we discuss with software we will decide to use
- Firmware
	- Klipper
 - 		Which hardware for the "Klipper PC" Raspberry Pi something or other???
- Marcos
- 	Auto bed meshing/leveling
-	Loading filament
-	Ejecting Filament
-	

## Physical Build
- Tuning
- 	Steps per mm per axis
- 	Sensorless homing
- Testing & QA
-	Create "Commissioning Test" to verify functionality of each piece individually (Similar to Prusa or Bambu POST)
- 	Use the newly created test to Verify everything does what it is supposed to
- Build Guide
- 	Create build steps documentation

## Documentation
- Build Guide
-	Create build steps documentation
- Bill of Material (BOM)
- 	List of equipment required to build this HT3D printer 
