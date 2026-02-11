# WO-012: Create Placeholder 1080i/Custom_1101_Hub_Movies.xml (Movies Hub)

## Description
Create a minimal placeholder XML file for the Movies Hub (`Custom_1101_Hub_Movies.xml`) within the `1080i` resolution folder. This file will eventually house the layout and controls for browsing and interacting with movie content. For now, it will be a simple, empty window definition.

## Files Touched
- `1080i/Custom_1101_Hub_Movies.xml`

## Acceptance Criteria
- A file named `Custom_1101_Hub_Movies.xml` exists within `skin.genesis/1080i/`.
- The `Custom_1101_Hub_Movies.xml` file contains a minimal, valid XML structure for a Kodi window (e.g., `<window><controls></controls></window>`).
- No specific content or advanced controls are present, aiming for a blank screen initially.

## Manual Visual Test Checklist
N/A (This is a non-visual, structural task. The window will not be visible until navigation to it is implemented in a later WO).
- Review Kodi's debug log for any XML parsing errors related to `Custom_1101_Hub_Movies.xml` after skin activation.