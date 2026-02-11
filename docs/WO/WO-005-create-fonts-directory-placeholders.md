# WO-005: Create fonts/ Directory and Placeholder Exo2 Files

## Description
Create the `fonts/` directory within the skin's root to house all font assets. As per the Genesis Vision, Exo2 is the only allowed font. This WO includes creating placeholder `.ttf` files to establish the file names and structure for the actual Exo2 font files, which will be sourced and placed later.

## Files Touched
- Creation of directory `fonts/`
- Creation of placeholder file `fonts/Exo2-Regular.ttf`
- Creation of placeholder file `fonts/Exo2-Bold.ttf`
- Creation of placeholder file `fonts/Exo2-Light.ttf`

## Acceptance Criteria
- A directory named `fonts/` exists directly within `skin.genesis/`.
- Placeholder files `Exo2-Regular.ttf`, `Exo2-Bold.ttf`, and `Exo2-Light.ttf` exist within the `fonts/` directory. These files can be empty or contain minimal, non-functional content.

## Manual Visual Test Checklist
N/A (This is a non-visual, structural task. Kodi will not use these empty placeholder files for rendering, but their presence confirms the directory structure).
- Verify directory and file creation using a file browser or command line.
- Note: Actual visual verification of font usage will occur in later WOs once real font files are integrated and applied to skin elements.