# Genesis Kodi Skin - Architecture

This document outlines the high-level architectural plan for the Genesis Kodi skin, focusing on initial window implementations, "In Progress" functionality, and watchlist management.

## Initial Window Implementation Priority

The following windows will be prioritized for initial implementation to establish core navigation and content browsing:

1.  **Home Screen (`Home.xml`):** The central entry point, providing quick access to primary hubs and essential information.
2.  **Movies Hub (`Custom_1101_Hub_Movies.xml`):** Dedicated view for browsing and interacting with movie content.
3.  **TV Shows Hub (`Custom_1102_Hub_TVShows.xml`):** Dedicated view for browsing and interacting with TV show content.
4.  **Anime Hub (`Custom_1103_Hub_Anime.xml`):** Dedicated view for browsing and interacting with anime content.

## "In Progress" Functionality

The "In Progress" feature will provide quick access to media that the user has started but not finished.

*   **Movies "In Progress":** Displays a tile or entry for movies that are partially watched. Clicking on the tile will resume playback from the last-watched position.
*   **TV Shows "In Progress":** Displays a series tile for TV shows where the user has unwatched episodes. Clicking on the series tile will *always* jump directly to the *next unwatched episode* within that series. This streamlines the "binge-watching" experience.

## Watchlist Management

Watchlists are a critical component for users to track content they intend to watch.

*   **Rule: Watchlists Live in Hubs, Not Home:** To keep the Home screen clean and focused on immediate content consumption ("In Progress", recently added), watchlists will reside exclusively within their respective content hubs (e.g., Movie Watchlist in Movies Hub, TV Show Watchlist in TV Shows Hub). This provides a clear organizational structure and prevents clutter on the main screen.