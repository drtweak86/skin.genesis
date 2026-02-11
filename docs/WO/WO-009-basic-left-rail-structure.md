# WO-009: Implement Basic Left Rail Structure on Home Screen

## Description
Integrate the fundamental XML structure for the Prime/Disney-style left navigation rail onto the `1080i/Home.xml` screen. This will involve creating a `control type="panel"` (or similar container control) positioned on the left side of the screen, serving as the visual foundation for menu items.

## Files Touched
- `1080i/Home.xml`

## Acceptance Criteria
- The `1080i/Home.xml` file contains a `<control type="panel">` (or `<control type="group">`) element within its `<controls>` section.
- This panel is positioned (`posx`, `posy`, `width`, `height`) to occupy the left-hand portion of the screen, covering the entire vertical extent.
- The panel has a distinct background color (e.g., solid black, possibly using a slightly different shade or opacity than the main background to create a visual separation), making it clearly visible against the main background.

## Manual Visual Test Checklist
1.  **Activate Skin:** Load the Genesis skin in Kodi.
2.  **Verify Left Panel:** Observe the home screen. A vertical, rectangular panel should be clearly visible on the far left side of the screen.
3.  **Check Dimensions:** Visually confirm the panel spans the entire height of the screen and occupies a reasonable width (e.g., 1/5th to 1/4th of the total screen width).
4.  **Background Distinction:** Ensure the panel's background color is distinguishable from the main screen background, even if subtle.
5.  **No Overlap/Clipping:** Confirm the panel does not overlap with any other intended content area (though none exist yet) or get clipped by screen edges.