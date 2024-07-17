
# Description
## HT3D4All

High Temperature 3d Printer for All or HT3D4All is the brain child of Smokintbird.
With 3d printers commercially available printing in materials like PLA, PETG, and ABS has become quite common.
However, when it comes to engineering grade filament (such as PEEK, PEKK, and other Nylon filaments) your standard off the shelf printer struggles to print functional parts.
# Goals

The goal here is to create an affordable 3D printer capable of printing high temperature engineering filaments. Current printers capable of turning out reliable parts from filaments such as PEKK, PSU, etc. cost several thousand of dollars (USD). Our goal is to have a higher quality print for a much lower cost. 

We are working to design a printer that will be the first on the market to create usable parts from PEKK, Peek or PEI for around $1,000 USD. Currently, the average price for a printer of this caliber sells for around $7,000 (USD). This means our goal is to create a high quality printer for less than 1/3 of the price!

3D printers capable of turning out usable parts from PEKK, PEEK, or PEI typically start around $7000 USD, so we are trying to design and build the first "affordable" printer to do it. (PEEK cost ~$500USD/1kg for perspective on affordable)

How can I get involved?

This is an exciting project that is very much on the ground floor, and we are looking for volunteers to make this a reality. We want to create an opensource plan that makes this technology available to people all over the world. To begin we need to create manuals, plans, diagrams, a bill of material (BOM) and more. We would love to have tech enthusiasts from all backgrounds to help on this project. Below is a detailed list of the steps that we are currently taking to make this a reality.  Reach out to us today on our page here for information and to connect. Feel free to just drop a message saying hi or with any of your own ideas! We love the idea of connecting with other techies. 


Before releasing plans, manuals, etc. this stuff must exist, so we are planning to create all that stuff AFTER producing a working, tested, & reproducible system that does the thing.


## Hardware
---
In this section we will discuss what hardware sections we will need to create
- Extruder
	- Which Off-The-Shelf extruder product?
	- Which Hot-End product do we want?
	-  Remote or direct drive?
		- Remote drive (think weed eater cable drive)
		- No Bowden tube as it has too much flex
- Kinematics
	- What kinematic system do we want to use?
		- We would like to use ball screws moving on linear rails.
- Heated Bed
	- Which heated bed are we going to use?
		- The bed will need to be able to reach temperatures of 150c with 100%duty cycle.
- Build Plate
	- What type of build plate will we be using?
		- There are a few options that we can choose from.
			- 1/4" minimum thickness Glass sheet
			- 1/8" minimum thickness Carbon Fiber sheet
			- 3/16" minimum thickness FR-4 (Circuit Board) sheet
- Frame
	- Q: What frame material will be used?
		- 20x20 standard aluminum rails with various hardware
- Mainboard
	- What mainboard will be used:
- Controller board
	- Will there be a controller board paired with the mainboard:
		- Yes! The controller board that will be commonly uses will be a Raspberry Pi 4 or 5. Preferably the 8gb model


## Software
---
This section will be where we discuss with software we will decide to use
- Firmware
	-  What firmware will be used?
		- Klipper is the firmware of choice.
- Marcos
	-  Will there be any macros available?

## Physical Build
---
- Tuning
- Steps per mm per axis
- Sensorless homing
- Testing & QA
- Create "Commissioning Test" to verify functionality of each piece individually (Similar to Prusa or Bambu POST)
- Use the newly created test to Verify everything does what it is supposed to
- Build Guide
- Create build steps documentation

## Documentation
---
- Build Guide
- Create build steps documentation
- Bill of Material (BOM)
- List of equipment required to build this HT3D printer