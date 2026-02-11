# WO-010: Add Basic Navigation Items to Left Rail (Home, Movies, TV Shows)

## Description
Populate the previously established left navigation rail in `1080i/Home.xml` with fundamental navigation entries. This WO focuses on adding simple text labels for "Home", "Movies Hub", and "TV Shows Hub" to provide an initial menu structure, without implementing any actual navigation functionality yet.

## Files Touched
- `1080i/Home.xml`

## Acceptance Criteria
- The left navigation panel in `Home.xml` now contains at least three distinct `<control type="label">` or similar text-displaying controls.
- These controls display the text "Home", "Movies", and "TV Shows" (or similar clear identifiers).
- The labels are clearly visible against the left rail's background.
- The labels are arranged vertically within the left rail.

## Manual Visual Test Checklist
1.  **Activate Skin:** Load the Genesis skin in Kodi.
2.  **Observe Left Rail:** Navigate to the home screen and examine the left navigation panel.
3.  **Verify Labels:** Confirm that the text labels "Home", "Movies", and "TV Shows" are present and legible.
4.  **Alignment & Spacing:** Check that the labels are vertically stacked and have reasonable spacing between them, appearing as a coherent menu.
5.  **No Overflows:** Ensure the text labels fit within the width of the left rail and do not get clipped.