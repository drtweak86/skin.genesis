# WO-007: Implement Default Black Background for Home Screen

## Description
Modify the `1080i/Home.xml` file to explicitly define a full-screen, solid black background. This aligns with the skin's black/red theme vision and ensures a consistent visual starting point for the home screen, even when no other elements are present.

## Files Touched
- `1080i/Home.xml`

## Acceptance Criteria
- The `1080i/Home.xml` file contains a `<control type="image">` element within the `<controls>` section.
- This image control is positioned to cover the entire screen (`posx="0" posy="0" width="1920" height="1080"` for 1080p).
- The image control's `texture` or `colordiffuse` attribute is set to render a solid black color (e.g., `colordiffuse="FF000000"`).

## Manual Visual Test Checklist
1.  **Install and Activate Skin:** Ensure the Genesis skin is installed and activated in Kodi.
2.  **Navigate to Home Screen:** Upon startup or navigating back to the home screen, observe the background.
3.  **Verify Solid Black:** The entire screen should be filled with a uniform, solid black color.
4.  **Check for Artifacts:** Ensure there are no visible borders, lines, gradients, or other non-black artifacts.
5.  **Performance Check:** Observe if adding the background control introduces any noticeable lag or stutter, though for a simple image control, this is unlikely.