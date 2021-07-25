# 3D Print Estimation Guide

## Basic Instructions

1.	Load STL into FlashPrint
2.	Move, rotate and otherwise generally align the STL file as needed and snap to ground.
3.	For overhangs or undercuts or other unsupported features, use Supports.
4.	To provide supports,    
	1. Click on Supports button
	2. Click Back to get to the main screen
	    1. go to Support option
	    2. select the type of support required (Treelike / Linear)
	    3. click OK button

	    OR
      4. Use Auto Supports

5.	Click on the Extruder button and select the correct extruder
6.	Click on the Print button
  a.	Select the correct extruder material (ABS, PLA, etc)
  b.	Select Supports, Raft, Resolution as appropriate
  c.	Select Advanced if needed.
  d.	Click Ok
7.	Save the .gx file
8.	Read off the estimated Time, Filament, Weight, etc.
9.	Save the .gx file into an SD card to load it on the printer.

Advanced Options

  ## Layer: 
  (Layer Height also selected automatically as per Print Resolution)

  Layer Height: 0.20mm

  First Layer Height: 0.30mm
  
  ## Shell:
  Perimeter shell: 3
  
  Top solid layer: 3
  
  Bottom Solid layer: 3

  ## Infill:
  Fill Density: 0-100% as per requirement
  
  Fill pattern: Hexagon or Line (Select as per required)

## Speed:
Print Speed: 60 mm/s

Travel: 80 mm/s

## Temperature:


|Material | Right Extruder Temperature (°C)	| Left Extruder Temperature (°C) | Platform temperature (°C)|
|--------|--------|--------|--------|
|ABS |	240 |	240 |	105|
|PLA |	250 |	250 |	55|
|Flexible Filament |	225-245 |	225-245 |	45-60|
|Dissolvable filament |	220-240 |	220-240 |	90-110|
