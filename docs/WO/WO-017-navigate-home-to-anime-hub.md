# WO-017: Implement Navigation from Home to Anime Hub

## Description
Integrate the necessary `onclick` or `onselect` actions into the "Anime" navigation item within the left rail of `1080i/Home.xml`. This action will trigger the opening of the `Custom_1103_Hub_Anime.xml` window, allowing users to transition to the dedicated anime browsing section. This WO assumes that an "Anime" navigation item has been added to the left rail (e.g., as part of a previous WO expanding the navigation menu).

## Files Touched
- `1080i/Home.xml`

## Acceptance Criteria
- An "Anime" navigation item is present and interactive in the left rail on `Home.xml`.
- Activating (clicking or selecting) the "Anime" item successfully closes `Home.xml` and opens `Custom_1103_Hub_Anime.xml`.
- When `Custom_1103_Hub_Anime.xml` is open, it appears as a blank screen (as it's currently a placeholder).
- Pressing the 'back' action (e.g., Escape key, back button on remote) from the Anime Hub correctly returns the user to the Home screen.

## Manual Visual Test Checklist
1.  **Activate Skin:** Load the Genesis skin in Kodi.
2.  **Navigate to Home:** Ensure the home screen is displayed.
3.  **Focus Anime Item:** Use navigation controls (keyboard arrows, remote) to focus on the "Anime" item in the left rail.
4.  **Select Anime Item:** Press Enter/OK to select the "Anime" item.
5.  **Verify Transition:** Observe that the screen changes from the Home screen to a blank (Anime Hub) screen.
6.  **Verify Back Navigation:** Press the 'back' button. Confirm that Kodi returns to the Home screen.
7.  **Error Check:** Monitor for any script or skin errors during the navigation process.