# Genesis Kodi Skin - Vision

This document outlines the core vision and guiding principles for the Genesis Kodi skin.

## Design Philosophy

*   **Prime/Disney-style Left Rail:** The primary navigation will be a persistent left-hand rail, inspired by the clean, intuitive interfaces of streaming services like Amazon Prime Video and Disney+. This rail will provide quick access to main hubs and core functionalities.
*   **Black/Red Theme:** The skin will utilize a sleek and modern black and red color palette. Black will serve as the dominant background, providing a premium feel, while red will be used for accents, highlights, and interactive elements to draw attention and provide visual cues.
*   **Exo2 Font Only:** To maintain a consistent and streamlined aesthetic, only the Exo2 font family will be used throughout the skin. There will be no font selector, ensuring a unified typographical experience.

## Performance Constraints (Pi-first)

Given the target audience often includes users with resource-constrained devices like the Raspberry Pi, performance is a critical consideration.

*   **Avoid Heavy Animations:** Complex or resource-intensive animations will be avoided. Subtle transitions and responsive feedback are preferred over flashy, demanding visual effects.
*   **No Large Textures:** Texture usage will be minimized, and where necessary, optimized for size and efficiency. This reduces memory footprint and speeds up rendering.
*   **Economical Conditional Logic:** XML conditional statements (e.g., `<visible>`) will be used judiciously. Overly complex or frequently evaluated conditions can impact performance, especially on slower hardware. Logic will be streamlined to ensure responsiveness.

## Data Sources

The skin will primarily leverage the following data sources for media information and tracking:

*   **TMDbHelper:** For comprehensive movie and TV show metadata, including artwork, cast, crew, ratings, and plot summaries.
*   **Trakt:** For synchronization of watched status, progress tracking, watchlists, and scrobbling. Trakt integration will be central to the "In Progress" functionality and watchlist management.