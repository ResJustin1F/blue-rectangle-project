# Blue Rectangle Project

## Overview  
This project showcases a three-step image manipulation sequence using Python and a custom graphics library. The goal is to demonstrate basic graphics generation, color gradient creation, and green screen replacement techniques.

## Project Structure  
The project includes the following steps:

### Step 1 – Create a Blue Rectangle  
Generates a solid blue rectangle image using Python and the `graphics.py` library.  
**Output:** `blue_rectangle.png`

### Step 2 – Create a Gradient Background  
Manipulates the blue rectangle into a background that transitions from red (top) to blue (bottom) using a loop-based pixel update.  
**Output:** `gradient_backdrop.png`

### Step 3 – Green Screen Removal and Image Compositing  
Loads `skater.png` (with a green screen) and overlays the skater onto the gradient background, removing the green pixels.  
**Output:** `skater_gradient.png`

## Files Included  
- `step1_p2-2.py`: Code for generating the blue rectangle  
- `step2_p2 copy.py`: Code for creating the gradient background  
- `step3_p2 copy.py`: Code for removing green screen and compositing  
- `graphics.py`: Required graphics library  
- `skater.png`: Image asset with green background  
- `blue_rectangle.png`, `gradient_backdrop.png`, `skater_gradient.png`: Output images

## Requirements  
- Python 3.x  
- `graphics.py` library in the same directory  
- Compatible with most IDEs (IDLE, VS Code, etc.)

## How to Run  
1. Ensure all `.py` files and image assets are in the same folder.  
2. Run each Python file in order:  
   - `step1_p2-2.py`  
   - `step2_p2 copy.py`  
   - `step3_p2 copy.py`  
3. Outputs will be saved automatically in the directory.

## Author  
Justin Restrepo
