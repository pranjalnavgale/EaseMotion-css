# Data Freshness Indicator States

A compact collection of dashboard components demonstrating status indicators for live, recently updated, stale, refreshing, and failed dataset states.

## Features Met
- **Dashboard Context:** Displayed cleanly alongside structural metric blocks and table headings.
- **Quiet Animations:** Implements a soft pulsating beacon for the `live` state and a continuous rotating ring for the `refreshing` state.
- **High Accessibility:** Includes age metrics text tags alongside color variations to ensure readability for colorblind users.
- **Collision Prevention:** Employs `white-space: nowrap` configurations and media-query logic to cleanly hide non-essential textual metadata on tiny screen resolutions.
- **Pure HTML/CSS:** 100% logic-free markup rendering.
- **Motion Mitigation:** Fully compliant wrapper logic tracking `prefers-reduced-motion` systems to eliminate visual animations gracefully.