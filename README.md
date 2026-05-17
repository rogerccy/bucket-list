# Bucket List

A personal bucket list tracker focused on the experiences you want to have — and when. Ties into the *Die With Zero* idea that timing matters: some things are best done at 30, others at 50.

**Live:** https://rogerccy.github.io/bucket-list/

## Features

- **Cards grouped by category** — items are organised into Travel, Adventure, Learning, Relationships, Creative, Career, Health, and Other
- **Rich item details** — each item tracks a title, category, age window (free text, e.g. "before 40" or "in my 50s"), estimated cost, notes, and status
- **Three statuses** — To Do, In Progress, and Done, each visually distinct
- **Filter tabs** — switch between All, Active (not done), and Done views
- **Mark done with animation** — clicking the checkmark button plays a pop animation and moves the item to the done state with a strikethrough
- **Stats bar** — shows completed, remaining, and total counts with a progress bar
- **Add / edit / delete** — modal panel for creating and editing items; keyboard shortcuts (Enter to save, Escape to close)
- **GitHub Gist sync** — all items are saved to a private Gist (`bucket-list.json`) and sync across devices
- **Local fallback** — works without a GitHub account via `localStorage`

## Setup

1. Open the app and paste a GitHub Personal Access Token with `gist` scope ([create one here](https://github.com/settings/tokens/new?scopes=gist&description=bucket-list))
2. Start adding items with the **+** button
3. Your list syncs automatically — open on any device with the same token to see everything

On a new device, enter the same token and the app finds your existing Gist by filename and restores your full list.
