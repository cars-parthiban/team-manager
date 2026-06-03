# Team Manager — GitHub Publishing Guide

**Your GitHub repo:** `https://github.com/cars-parthiban/team-manager`  
**Your live app URL:** `https://cars-parthiban.github.io/team-manager`

---

## First-Time Setup (Already Done)

You've already created the GitHub repo. This is a one-time setup — you never need to do this again.

---

## How to Upload / Update the App

Use this every time you have a new version of the HTML file (v2, v3, etc.)

### Step 1 — Rename the file
Before uploading, rename your HTML file to `index.html` on your computer.
- `TeamManager_v1.html` → rename to → `index.html`
- Always use `index.html` — GitHub Pages requires this exact name to serve it as a website

### Step 2 — Go to your repo
Open [github.com/cars-parthiban/team-manager](https://github.com/cars-parthiban/team-manager)

### Step 3 — Upload the file
- If the repo is **empty:** click **"uploading an existing file"** in the Quick Setup box
- If the repo **already has files:** click **Add file → Upload files**

### Step 4 — Drop the file and commit
1. Drag and drop `index.html` into the upload area (or click "choose your files")
2. If an `index.html` already exists, it will be replaced — that's correct
3. Scroll down to **Commit changes**
4. Leave the default message or type something like `Update to v2`
5. Click **Commit changes**

### Step 5 — Enable GitHub Pages (first time only)
> Skip this step if you've already done it once — the setting stays permanently.

1. Click **Settings** tab (top of the repo page)
2. Click **Pages** in the left sidebar
3. Under "Source" select **Deploy from a branch**
4. Set Branch to **main**, folder to **/ (root)**
5. Click **Save**

### Step 6 — Wait ~1 minute
GitHub takes about 60 seconds to publish. Then open:

```
https://cars-parthiban.github.io/team-manager
```

Your team can bookmark this link — it never changes even when you upload new versions.

---

## Sharing With Your Team

Just send them this link:
```
https://cars-parthiban.github.io/team-manager
```

- Works in any browser, on any device
- No download needed
- When you upload a new version, they automatically get it on next refresh
- No need to reshare the link

---

## Updating the App in the Future

When Claude produces a new `TeamManager_v2.html` (or v3, etc.):

1. Download the new file from Claude
2. Rename it to `index.html`
3. Go to [github.com/cars-parthiban/team-manager](https://github.com/cars-parthiban/team-manager)
4. Click **Add file → Upload files**
5. Drop the new `index.html` — it replaces the old one
6. Commit changes
7. Wait ~1 minute → live at the same URL

---

## Quick Reference

| What | Where |
|------|-------|
| GitHub repo | github.com/cars-parthiban/team-manager |
| Live app URL | cars-parthiban.github.io/team-manager |
| File to upload | Always named `index.html` |
| Time to go live after upload | ~1 minute |
| Team bookmark | cars-parthiban.github.io/team-manager |

---

## Troubleshooting

| Problem | Fix |
|---------|-----|
| URL shows 404 | GitHub Pages not enabled yet — go to Settings → Pages and set branch to main |
| Old version still showing | Hard refresh the browser: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac) |
| Changes not live after 5 min | Check the **Actions** tab in GitHub — look for a green checkmark confirming deployment |
| Accidentally deleted the repo | Recreate it at github.com/new, re-upload index.html, re-enable Pages |
