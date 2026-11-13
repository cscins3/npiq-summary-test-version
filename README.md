# NPI-Q SUMMARY — larger tap targets + Copy Report + Reset

This is a standalone, static `index.html` for GitHub Pages, based on the existing 12-item NPI-Q Summary test version.

## Updates
- Larger checkbox/radio controls (23×23 px) and full-cell click/touch areas (at least 58 px tall).
- Numeric hints (0–3 and 0–5) directly in each scoring cell.
- **Generate Summary** maintains the previous English report structure.
- **Copy Report** regenerates the current report, then copies it to the clipboard with confirmation.
- **Reset** clears all selections, disables radio choices until Yes is selected again, resets totals to zero, and clears the report.
- Small screens can scroll horizontally to access all scores.

## Upload to GitHub
1. Open https://github.com/cscins3/npiq-summary-test-version
2. On the `main` branch, choose **Add file → Upload files**.
3. Upload the `index.html` file **from this ZIP's root** (and optionally `README.md`). The filename must remain `index.html`.
4. Commit the changes and allow GitHub Pages to update.
5. Refresh https://cscins3.github.io/npiq-summary-test-version/ (hard refresh if cached).

Do not upload the ZIP as-is to the repository expecting GitHub Pages to unpack it: extract the ZIP first and upload the files.

No external libraries or build process needed. Clipboard permission may depend on browser settings; GitHub Pages uses HTTPS and supports normal clipboard access.
