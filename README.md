# CrumbCatcher

Cross-platform URL fragment search across multiple browsers.

Purpose:
- Prompt the user for a URL fragment.
- Search history and bookmarks across supported browsers (Gecko and Chromium families).
- Deduplicate results and export them to a timestamped SQLite file:
    Crumbs_YYYY-MMM-DD_HH-MM-SS.sqlite

Supported systems: Windows, macOS, Linux.
Supported browsers: Firefox (and forks), Chrome, Edge, Brave, Opera, Vivaldi, Ungoogled-Chromium.
No external dependencies; Python 3.8+ recommended.

Output schema (table `entries`):
  id | type | name | url | profile
