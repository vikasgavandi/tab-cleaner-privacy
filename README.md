# Tab Cleaner v1.3

Chrome Manifest V3 extension for finding duplicate/similar tabs, cleaning them up, and restoring recently closed sessions.

## UI
The popup is redesigned to match the supplied Tab Cleaner reference:
- Blue/white product header
- Duplicate Tabs overview card
- Duplicate count and red bulk-close action
- Compact memory/tab metrics
- Search + Restore Last controls
- Grouped duplicate-tab cards with favicon, URL, memory, status and actions
- Recently Closed section with individual Restore and Restore all

## Install
1. Extract the ZIP.
2. Open chrome://extensions.
3. Enable Developer mode.
4. Remove the older Tab Cleaner version.
5. Choose Load unpacked.
6. Select the extracted tab-cleaner folder.

## Permissions
The extension uses `tabs`, `processes`, and `sessions`. Chrome may not expose a reliable per-tab memory value; the UI shows — when unavailable.


## Chrome Web Store publication notes

Version 1.5 removes the unused `storage` permission and the non-stable `processes` permission.
The extension does not use remote code or external services.

Per-tab memory is displayed as unavailable (`—`) because the stable Chrome Extensions API
does not provide a reliable per-tab memory value. The extension does not fabricate memory values.
