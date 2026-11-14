# Garcon UI pull request screenshots

Screenshots captured with headless Chrome from isolated Garcon test fixtures on 2026-11-14.
All chat content, project names, paths, and executor identities are synthetic. No personal
Garcon workspace or browser profile was used.

The images live on a dedicated assets branch so the product pull requests contain only
their implementation and tests. Pull request descriptions embed images at this commit.

- `tables-*`: Markdown table padding, including desktop and mobile. The before image
  restores the original CSS cascade in the rendered fixture page; after images use the
  branch's production CSS.
- `alignment-*`: Left and Right alignment on desktop and mobile, plus the Appearance selector.
- `saved-projects-*`: New Chat landing at 1440, 390, and 360 pixels, on Local and both
  remote executor connection directions.
- `project-plus-*`: Sidebar project action on desktop and mobile, on Local and both
  remote executor connection directions.
