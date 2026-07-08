# Dealer OS Executive Light + Service Daily

Upload `index.html` to the root of your GitHub Pages repo.

This build keeps the Executive Light visual theme and adds the Service Daily / End of Day upload and section.

Files required in root:
- index.html
- README.md


## Sales Activity Fix
- Recognises dated SalesActivity exports such as `SalesActivity 08-07-26.xls`.
- Handles the Toyota HTML `.xls` headings `Enq's`, `T/D`, `O/S`, and `O`.
- Trade remains visible separately, but should be treated carefully against used target logic.
