# TexFlow - PBR Texture Manager

## Repository
https://github.com/Tauhmant/TexFlow-PBR-Texture-Manager

## Description
TexFlow is a Python desktop app that help 3D artists aitomatically indentify, rename, and organize texture files. All your texture files in one simple library which simplifies texture management, especially when working with software like Maya 3D, Blender and Unreal Engine.

## Features
- Folder Scanner
	- Allows user to scan a specific folder for supported texture files
- Texture Recognition
	- Identify comming PBR textures
- Automatic Ogranization
	- Groups related textures into folders based on their material names and texture types
- Automatic Renaming
	- Renames texture files using a consistent naming convention to make them easier to identify and use
- Texture Preview
	- Displays thumbnails of selected textures
- Missing Texture Detection
	- Shows which common texture maps are missing from a material's texture set

## Challenges
- Python's os and pathlib library
- Pillow library to load, resize and display textures
- Handling unexpected filenaming issues, duplicate files etc.

## Outcomes
Ideal Outcome:
- A fully functional desktop application with a user-friendly interface that can recognize, preview, rename, and organize multiple PBR texture sets automatically

Minimal Viable Outcome:
- A working Python app that allows users to to select a folder and indentifies basic files and groups them.

## Milestones

- Week 1
  1. Research PBR textures
  2. Develop the basic folder scanning and texture recognintion system

- Week 2
  1. Implement automatic file organiztion and renaming
  2. Test the program with different texture sets

- Week 3
  1. Add GUI
  2. Add texture previews using the Pillow library

- Week 4 (Final)
  1. Implement missing texture detection
  2. Text the complete app
