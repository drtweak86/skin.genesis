# WO-019: Implement Basic "In Progress" Widget Placeholder on Home Screen (TV Shows)

## Description
Create a simple, static placeholder widget on the `Home.xml` screen to represent the "TV Shows In Progress" section. Similar to the movie counterpart, this widget will initially consist of a text label indicating its purpose and position, serving as a visual marker for where dynamic content (TV shows with unwatched episodes) will eventually be displayed. It should be positioned clearly outside the left navigation rail and distinct from the "Movies In Progress" widget.

## Files Touched
- `1080i/Home.xml`

## Acceptance Criteria
- The `1080i/Home.xml` file contains a `<control type="label">` element or similar text-displaying control for TV shows.
- This control displays the text "TV Shows In Progress" (or a similar clear identifier).
- The "TV Shows In Progress" label is clearly visible on the Home screen.
- The label is positioned outside the left navigation rail, in the main content area of the screen, and is visibly distinct from the "Movies In Progress" widget (e.g., positioned below or to the side).
- The label uses the skin's defined text styling (font and color).

## Manual Visual Test Checklist
1.  **Activate Skin:** Load the Genesis skin in Kodi.
2.  **Observe Home Screen:** Navigate to the home screen.
3.  **Verify Widget Presence:** Confirm that a text label "TV Shows In Progress" is clearly visible.
4.  **Position Check:** Ensure the label is located in the main content area, does not overlap with the left navigation rail, and is arranged logically relative to the "Movies In Progress" widget.
5.  **Styling Check:** Verify the text uses the correct Exo2 font and neutral text color as defined in `Includes.xml`.