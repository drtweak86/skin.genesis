# WO-001: Initial addon.xml Structure

## Description
Create the foundational `addon.xml` file for the Genesis Kodi skin, defining its unique identifier, name, version, and dependencies. This file is crucial for Kodi to recognize and load the skin.

## Files Touched
- `addon.xml`

## Acceptance Criteria
- A file named `addon.xml` exists in the skin's root directory (`skin.genesis/`).
- The `addon.xml` file contains the `<addon>`, `<requires>`, and `<extension>` root tags correctly structured.
- The `<addon>` tag has `id="skin.genesis"`, `name="Genesis"`, `version="0.0.1"`, and `provider-name="drtweak86"`.
- The `<requires>` section includes a dependency for `xbmc.gui` with a minimum version compatible with Kodi Omega (e.g., `5.16.0`).
- The `<extension point="xbmc.gui.skin">` tag defines the skin type and provides a default path.

## Manual Visual Test Checklist
N/A (This is a non-visual, foundational configuration task).