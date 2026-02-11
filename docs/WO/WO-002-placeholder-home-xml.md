# WO-002: Create Placeholder 1080i/Home.xml

## Description
Create a minimal placeholder `Home.xml` file within the `1080i` resolution folder. This file serves as the initial entry point for the skin's main home screen when activated in Kodi. It should be as simple as possible to ensure a blank, functional canvas.

## Files Touched
- `1080i/Home.xml`

## Acceptance Criteria
- A directory `1080i/` exists in the skin's root (`skin.genesis/1080i/`).
- A file named `Home.xml` exists within `skin.genesis/1080i/`.
- The `Home.xml` file contains a minimal, valid XML structure for a Kodi window (e.g., `<window><controls></controls></window>`).
- No specific content or advanced controls are present, aiming for a blank screen initially.

## Manual Visual Test Checklist
1.  **Install Skin:** Copy the `skin.genesis` folder into Kodi's `addons` directory.
2.  **Activate Skin:** Navigate to Kodi's Interface settings, select "Skin," and switch to "Genesis."
3.  **Verify Blank Screen:** After activating, Kodi should restart and display a blank, black screen (or the default background color if not explicitly set to black).
4.  **Error Check:** Ensure no Kodi error notifications (e.g., "Skin Shortcuts error," "Script error") appear upon startup or while navigating to the home screen.
5.  **Log Check:** Review Kodi's debug log for any XML parsing errors related to `Home.xml`.