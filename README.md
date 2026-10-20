# Blood Donation Heroes Draw 2026

A lucky-draw page for a blood donation drive. Upload the donor list, then draw winners one at a time with confetti.

## Features
- Upload a donor list as an Excel file (`.xlsx`). Names are read from the first column of the first sheet, and the header row is skipped
- Shows how many donors were loaded
- Draws numbered winners at random, with a confetti celebration

## Tech stack
HTML, CSS and JavaScript, using [SheetJS](https://sheetjs.com/) (`xlsx` 0.18.5) and `canvas-confetti` from CDNs.

## Run
1. Open `index.html` in a browser (it needs internet access for the CDN scripts).
2. Click **Upload Donor List** and pick your `.xlsx` file.
3. Draw winners.
