# WO-018: Implement Basic "In Progress" Widget Placeholder on Home Screen (Movies)

## Description
Create a simple, static placeholder widget on the `Home.xml` screen to represent the "Movies In Progress" section. This widget will initially consist of a text label indicating its purpose and position, serving as a visual marker for where dynamic content (movies that are partially watched) will eventually be displayed. It should be positioned clearly outside the left navigation rail.

## Files Touched
- `1080i/Home.xml`

## Acceptance Criteria
- The `1080i/Home.xml` file contains a `<control type="label">` element or similar text-displaying control.
- This control displays the text "Movies In Progress" (or a similar clear identifier).
- The "Movies In Progress" label is clearly visible on the Home screen.
- The label is positioned outside the left navigation rail, in the main content area of the screen.
- The label uses the skin's defined text styling (font and color).

## Manual Visual Test Checklist
1.  **Activate Skin:** Load the Genesis skin in Kodi.
2.  **Observe Home Screen:** Navigate to the home screen.
3.  **Verify Widget Presence:** Confirm that a text label "Movies In Progress" is clearly visible.
4.  **Position Check:** Ensure the label is located in the main content area and does not overlap with the left navigation rail.
5.  **Styling Check:** Verify the text uses the correct Exo2 font and neutral text color as defined in `Includes.xml`.