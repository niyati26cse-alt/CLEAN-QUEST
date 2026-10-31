# CLEAN QUEST

A hackathon-ready, browser-based gamified file organizer MVP.

## Run it
1. Extract `CLEAN_QUEST.zip`.
2. Open `index.html` in Chrome, Edge, or Firefox.
3. No installation, account, API key, or server is required.

For the best demo, use a recent Chrome or Edge browser.

## Demo flow
1. Open **File Organizer**.
2. Click **Load demo files** or upload files from your device.
3. Open **Play Game** and start the 60-second sorting quest.
4. Sort file cards into the correct category bins.
5. Open **Results** and download the organized ZIP.
6. Open the ZIP to verify the category folders and file contents.

## What works
- Multi-file upload and drag-and-drop.
- Local file categorization by extension and MIME type.
- Sorting game with timer, scoring, and XP.
- XP, levels, and game counters saved in localStorage.
- Actual ZIP archive creation in the browser, including original file contents.
- Demo files for a quick presentation.
- Responsive layout for desktop and mobile.

## Important technical note
This MVP uses deterministic file-type detection (extensions and MIME types), not a hosted generative AI model. The app does not transmit user files to a server. Describe it accurately as a **gamified smart file-automation prototype** unless you add and test a real AI integration.

## Privacy
Files are processed locally in the browser. Do not upload confidential or sensitive files to a public demo device.
