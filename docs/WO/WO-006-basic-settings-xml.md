# WO-006: Create Basic resources/settings.xml

## Description
Create a minimal `settings.xml` file within the `resources/` directory. This file is where all configurable options for the skin will be defined. While not strictly necessary for a "blank home screen," establishing this file early provides a structured location for future customization, adhering to best practices for Kodi skin development.

## Files Touched
- `resources/settings.xml`

## Acceptance Criteria
- A directory `resources/` exists in the skin's root (`skin.genesis/resources/`).
- A file named `settings.xml` exists within `skin.genesis/resources/`.
- The `settings.xml` file contains a minimal, valid XML structure for skin settings (e.g., `<settings><category id="general"></category></settings>`).
- No specific settings are defined beyond a basic category, aiming for an empty but functional settings structure.

## Manual Visual Test Checklist
N/A (This is a non-visual, structural task. Kodi's settings interface will only show entries once actual `<setting>` tags are added).
- Verify directory and file creation using a file browser or command line.
- After skin activation in Kodi, attempt to navigate to the skin settings (usually System -> Interface -> Skin -> Configure skin...). Ensure no errors appear when trying to open the settings dialog, even if it's empty.