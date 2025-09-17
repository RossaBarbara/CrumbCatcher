# CrumbCatcher
CrumbCatcher – a multi-browser history &amp; bookmark extractor. Query Firefox, Chrome, Edge, Brave, Opera (and more) for specific URLs or domains, export results to SQLite, and trace your digital breadcrumb trails.

# CrumbCatcher

CrumbCatcher is a cross-browser history and bookmark extractor.  
It allows you to search for any URL fragment (such as `google.com` or `comick.io/comic/`) across multiple browsers and exports the results into a SQLite database.

---

## Features
- Search by any URL fragment (e.g. `youtube.com`, `reddit.com/r/python`)
- Works with multiple browsers:
  - Firefox
  - Chrome
  - Edge
  - Brave
  - Opera
- Extracts from both history and bookmarks
- Exports results to `results_lookup.sqlite` (viewable with [DB Browser for SQLite](https://sqlitebrowser.org/))
- Deduplicates automatically
- Prints a summary report of what was found per browser
- Safe handling of existing output files (overwrite, backup, or abort)

---

## Usage

### 1. Clone the repository
```bash
git clone https://github.com/your-username/CrumbCatcher.git
cd CrumbCatcher
