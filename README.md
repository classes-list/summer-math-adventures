# Rising Stars Math Adventures

A 5-week interactive summer math program for rising 4th and 5th graders, designed for
Mary, Star of the Sea School (Summer 2026).

🌟 **Live site:** https://classes-list.github.io/summer-math-adventures/

## What it is

A single-page web app with:

- **Program Overview** for parents and admin — five themed lands (Lost Island, Temple of
  Fractions, Cave of Decimals, Sky Kingdom of Geometry, Space Station of Stars), daily
  schedule, materials list, FAQ.
- **Adventure Lessons** for students — all 25 days of practice missions, auto-graded,
  with a retry-with-new-problems system that requires a perfect 5 / 5 to earn each
  supply and badge.
- **Multi-profile localStorage** — multiple students can share a device with separate
  progress. Each picks their explorer name and avatar.
- **Export / Import progress to a JSON file** — students can take their progress home
  on a USB stick, in Google Drive, or via email.
- **Email accomplishments to teachers** — every completed lesson can be emailed
  (via Gmail compose) to both Ms. Glavan and Dr. Park with the student's name, lesson,
  supply earned, badge unlocked, and total attempts.

## Files

- `index.html` &mdash; the entire app. Single self-contained file. No backend.

## Tech

Pure HTML / CSS / JavaScript. No build step, no dependencies, no external libraries.
Works offline once loaded. Progress saved in browser `localStorage` keyed by
explorer profile.

## Credits

Designed by **Dr. Peter Park** &middot; Mary, Star of the Sea School &middot; Summer 2026.
