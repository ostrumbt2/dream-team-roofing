# Dream Team Roofing — Door Log

A single-file web app for tracking door-knocking canvassing: addresses visited,
visit status, damage found, feedback given, and how the customer interaction went.

## Features
- Log every address knocked with date, rep name, and visit status (Knocked / No Answer / Callback / Job Completed / Not Interested)
- Record damage found (missing shingles, hail, wind, leaks, flashing/gutter, or none visible)
- Track customer interaction quality (Positive / Neutral / Negative / Hostile) plus free-text notes
- Search and filter the log by status or keyword
- Running stats: doors logged, jobs completed, damage found, close rate
- Export/import your data as a JSON file (handy for backup or sharing between devices)

## How it stores data
This app saves everything in the browser's local storage — no server or database
required. That means data is tied to **one browser on one device**. Use the
**Export JSON** button regularly to back up your log, and **Import JSON** to bring
it into another browser/device.

## How to add this to your GitHub repo

**Option A — GitHub website (no command line needed)**
1. Go to https://github.com/ostrumbt2/dream-team-roofing
2. Click **Add file → Upload files**
3. Drag in `index.html` (and this `README.md` if you'd like)
4. Scroll down and click **Commit changes**

**Option B — Command line**
```bash
git clone https://github.com/ostrumbt2/dream-team-roofing.git
cd dream-team-roofing
# copy index.html into this folder
git add index.html README.md
git commit -m "Add door log tracking app"
git push
```

## How to host it live (free, via GitHub Pages)
1. In your repo, go to **Settings → Pages**
2. Under "Build and deployment," set **Source** to `Deploy from a branch`
3. Choose the `main` branch and `/ (root)` folder, then **Save**
4. GitHub will give you a URL like `https://ostrumbt2.github.io/dream-team-roofing/`
   — that's your live app, usable from any phone or laptop browser.

## Notes
- Works on mobile browsers, so reps can log doors right from the driveway.
- No sign-in, no backend — just open the page and start logging.
