# <center>Project: Game of Life</center>
**Author:** Charles Holdren<br>
**Email:** CFHoldren@student.fullsail.edu<br>
**Education:** Full Sail University <br>
![Degree Program](https://img.shields.io/badge/certificate-Application%20Development%20Fundamentals-darkgreen.svg)<br>
![Degree Program](https://img.shields.io/badge/degree-Computer%20Science%20Bachelor's-blue.svg)<br>

## Overview
This project was created for the course Project and Portfolio I: Online at Full Sail University.

## Updates
### 07/06/2021
- Colors now show preview.
### 07/05/2021
- Added shortcuts for most buttons.
- Settings Autosave during runtime.
- Settings save previous settings file upon closing.
- User can manually change size of universe through settings.
- Added about box under Help.
- User now has 3 cursor options, Single-Click, Paint, and Erase.
### 07/04/2021
- Implemented Neighbor Count overlay.
- User can change interval.
- Implemented Open and Save As.
- User can now import .cells file (PlainText)
### 07/03/2021
- Made improvements to randomization options, added text box to input seed.
- HUD feature implemented.
### 07/02/2021
- Implemented 10x Grid display.
- Added a context menu strip to the graphics panel.
- Implemented randomize options dependent on seed.
### 07/01/2021
- Both torodial and finite boundry types have been successfully implemented.
### 06/30/2021
- Created Icons for Play, Pause and Next. Added Play and Next to tool strip.
- Created a method for loading user settings and one for creating a new file if it doesn't exist.
- Start / Pause options toggle states in GUI.
- Added the basic logic for the game rules, Start / Pause work correctly.
- Added functionality to the next button.
- Mousewheel scroll now changes grid size.
- HUD now displays cell count.
### 06/29/2021
- Installed project template to Visual Studio.
- Create the root markdown file.
- Create a GitHub repository.
- Push the project onto the repository.
- Smoother window scaling, updated cell width and height to be calculated as floats.
- Added functionality to the "New" option.

## Requirements
### Cell Behavior (Rules)
- [X] Living cells with less than 2 living neighbors die in the next generation.
- [X] Living cells with more than 3 living neighbors die in the next generation.
- [X] Living cells with 2 or 3 living neighbors live in the next generation.
- [X] Dead cells with exactly 3 living neighbors live in the next generation.
### Minimum Requirements for Milestone 1
- [X] Render Conway�s Game of Life in a .NET application.
- [X] Grid and cells displaying correctly.
- [X] Cells can be toggled (on/off) by clicking with the mouse.
- [X] Cells live or die according to the four rules listed above.
- [X] Add functionality to the Start button.
- [X] Add functionality to the Pause button.
- [X] Add functionality to the Next button.
- [X] Add functionality to the New button.
### Additional Project Requirements
- [X] Implement a HUD that displays current generation, cell count, boundary type, and universe size.
- [X] Add functionality to the Open button.
- [X] Add functionality to the Save button.
- [X] Add functionality to Import.
- [X] The ability to randomize by new seed, current seed or generate seed based on time.
- [X] Display the current generation. 
- [X] Display the number of living cells.
- [X] User can adjust game speed.
- [X] Able to change grid size.
- [X] Display the neighbor count in each cell.
- [X] Toggle the neighbor count (on/off) in the View menu.
- [X] Toggle the grid (on/off) in the View menu. 
- [X] Toggle the HUD (on/off) in the View menu.
- [X] The ability to change the colors for grid, background and cells.
- [X] Implement toroidal universe boundries.
- [X] Implement finite universe boundries.
- [X] Implement a ContextMenuStrip that allows the user to change various options in the application.