# CrumbCatcher

CrumbCatcher is a cross-browser history and bookmark extractor.  
It allows you to search for any URL fragment (such as `google.com` or `comick.io/comic/`) across multiple browsers and exports the results into a SQLite database.

---

## Features
- Search by any URL fragment (e.g. `youtube.com`, `reddit.com/r/python`)
- Works across platforms: **Windows, Linux, macOS**
- Supports multiple browsers:
  - Firefox, Waterfox, LibreWolf, Pale Moon
  - Chrome, Edge, Brave, Opera, Vivaldi, Ungoogled-Chromium
- Extracts from both history and bookmarks (where supported)
- Deduplicates automatically across browsers and profiles
- Exports results to a timestamped SQLite database:  
  `Crumbs_YYYY-MMM-DD_HH-MM-SS.sqlite`
- Prints a summary report of:
  - total records found
  - duplicates removed
  - unique entries saved

---

## Usage

### 1. Clone the repository
```bash
git clone https://github.com/your-username/CrumbCatcher.git
cd CrumbCatcher
