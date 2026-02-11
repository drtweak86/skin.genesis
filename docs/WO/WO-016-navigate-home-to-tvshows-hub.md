# WO-016: Implement Navigation from Home to TV Shows Hub

## Description
Integrate the necessary `onclick` or `onselect` actions into the "TV Shows" navigation item within the left rail of `1080i/Home.xml`. This action will trigger the opening of the `Custom_1102_Hub_TVShows.xml` window, allowing users to transition to the dedicated TV show browsing section.

## Files Touched
- `1080i/Home.xml`

## Acceptance Criteria
- The "TV Shows" navigation item in the left rail on `Home.xml` is interactive.
- Activating (clicking or selecting) the "TV Shows" item successfully closes `Home.xml` and opens `Custom_1102_Hub_TVShows.xml`.
- When `Custom_1102_Hub_TVShows.xml` is open, it appears as a blank screen (as it's currently a placeholder).
- Pressing the 'back' action (e.g., Escape key, back button on remote) from the TV Shows Hub correctly returns the user to the Home screen.

## Manual Visual Test Checklist
1.  **Activate Skin:** Load the Genesis skin in Kodi.
2.  **Navigate to Home:** Ensure the home screen is displayed.
3.  **Focus TV Shows Item:** Use navigation controls (keyboard arrows, remote) to focus on the "TV Shows" item in the left rail.
4.  **Select TV Shows Item:** Press Enter/OK to select the "TV Shows" item.
5.  **Verify Transition:** Observe that the screen changes from the Home screen to a blank (TV Shows Hub) screen.
6.  **Verify Back Navigation:** Press the 'back' button. Confirm that Kodi returns to the Home screen.
7.  **Error Check:** Monitor for any script or skin errors during the navigation process.