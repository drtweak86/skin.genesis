# WO-008: Define Basic Skin Properties (Colors, Fonts) in Includes.xml

## Description
Begin defining global skin properties such as standard color definitions (e.g., black, red, primary text color, accent color) and font styles (e.g., Exo2-Regular, Exo2-Bold, Exo2-Light with specific sizes) within `1080i/Includes.xml`. Centralizing these definitions will ensure consistency across the skin and facilitate easy theme adjustments in the future.

## Files Touched
- `1080i/Includes.xml`

## Acceptance Criteria
- The `1080i/Includes.xml` file contains `<include>` blocks for common color definitions.
- Hexadecimal color codes are defined for the primary black background, accent red, and at least one neutral text color.
- The `Includes.xml` file contains `<include>` blocks for font definitions.
- Font definitions are created for `Exo2-Regular`, `Exo2-Bold`, and `Exo2-Light`, referencing the placeholder `.ttf` files created in WO-005.
- Each font definition includes appropriate font sizes for various UI elements (e.g., heading, body, small text).

## Manual Visual Test Checklist
N/A (This is a non-visual, definitional task. The actual visual impact of these definitions will be observed in subsequent WOs where these colors and fonts are applied to specific UI controls).
- Review Kodi's debug log for any XML parsing errors after adding these include blocks to `Includes.xml`. Ensure the skin still loads without errors.