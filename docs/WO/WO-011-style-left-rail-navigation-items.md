# WO-011: Style Left Rail Navigation Items (Black/Red Theme)

## Description
Apply the Genesis skin's black/red theme and Exo2 font definitions to the navigation items displayed in the left rail on the home screen. This will involve using the defined colors (from WO-008) for text and potentially background/highlight elements, and referencing the Exo2 font styles to ensure a consistent and branded look.

## Files Touched
- `1080i/Home.xml`
- (Potentially) `1080i/Includes.xml` if new specific styles for navigation items are defined as reusable includes.

## Acceptance Criteria
- The text labels for "Home", "Movies", and "TV Shows" in the left rail use one of the Exo2 font definitions (e.g., Exo2-Regular or Exo2-Light) as defined in `Includes.xml`.
- The default text color for these items is the defined neutral text color (e.g., light grey or white).
- When a navigation item is focused or hovered over, its text color changes to the defined accent red color.
- (Optional but desirable) A subtle background highlight appears on the focused/hovered item, adhering to the black/red theme.

## Manual Visual Test Checklist
1.  **Activate Skin:** Load the Genesis skin in Kodi.
2.  **Observe Left Rail:** Navigate to the home screen and examine the left navigation panel.
3.  **Verify Font Usage:** Visually confirm that the font used for the navigation items is Exo2 (e.g., by comparing to known Exo2 characteristics or previous skins).
4.  **Default Color:** Ensure the unselected navigation items display in the designated neutral text color.
5.  **Focus/Hover Color:** Use a remote or mouse to navigate and highlight each menu item. Verify that the text color (and background if implemented) changes to the accent red when focused/hovered.
6.  **Legibility:** Confirm that all text remains clearly legible against the background in both default and focused states.