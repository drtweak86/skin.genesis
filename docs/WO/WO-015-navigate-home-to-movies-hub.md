# WO-015: Implement Navigation from Home to Movies Hub

## Description
Integrate the necessary `onclick` or `onselect` actions into the "Movies" navigation item within the left rail of `1080i/Home.xml`. This action will trigger the opening of the `Custom_1101_Hub_Movies.xml` window, allowing users to transition to the dedicated movie browsing section.

## Files Touched
- `1080i/Home.xml`

## Acceptance Criteria
- The "Movies" navigation item in the left rail on `Home.xml` is interactive.
- Activating (clicking or selecting) the "Movies" item successfully closes `Home.xml` and opens `Custom_1101_Hub_Movies.xml`.
- When `Custom_1101_Hub_Movies.xml` is open, it appears as a blank screen (as it's currently a placeholder).
- Pressing the 'back' action (e.g., Escape key, back button on remote) from the Movies Hub correctly returns the user to the Home screen.

## Manual Visual Test Checklist
1.  **Activate Skin:** Load the Genesis skin in Kodi.
2.  **Navigate to Home:** Ensure the home screen is displayed.
3.  **Focus Movies Item:** Use navigation controls (keyboard arrows, remote) to focus on the "Movies" item in the left rail.
4.  **Select Movies Item:** Press Enter/OK to select the "Movies" item.
5.  **Verify Transition:** Observe that the screen changes from the Home screen to a blank (Movies Hub) screen.
6.  **Verify Back Navigation:** Press the 'back' button. Confirm that Kodi returns to the Home screen.
7.  **Error Check:** Monitor for any script or skin errors during the navigation process.