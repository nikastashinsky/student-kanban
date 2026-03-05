# Kanban

A minimal, playful kanban board for staying organized. Built as a single-file PWA — works in the browser, installs to your home screen, and runs fully offline.

**Live:** https://nikastashinsky.github.io/mindful-kanban/

---

## Features

### Boards
- **Multiple workspaces** — create separate boards for different projects or areas of life
- Click a board name to rename it inline
- Delete boards you no longer need

### Columns
- **Dynamic swim lanes** — add, delete, and rename any column
- Default columns (To Do, In Progress, Done) can all be modified or removed
- Columns fill the screen evenly with few lanes; scroll horizontally when there are many

### Cards
- **Drag and drop** cards between columns and to reorder
- Click any title or description to edit inline
- **Tags**: cycle between task, idea, project
- **Color accent** per card (5 colors, via dropdown)
- **Priority asterisk** — tap ✳ to mark a card as high priority (turns blue)
- **Checklists** — add sub-tasks inside any card; Enter to add, Backspace on empty to remove
- **Archive** — done items can be moved to a hidden archive, toggled open at the bottom; archiving plays a celebratory stamp + shatter animation

### Search
- **Cmd+K** (or the search button) opens a global search across all boards, columns, and checklist items

### Daily Journal
- Trigger via the journal icon (top right); expand to fullscreen via the button at the bottom of the panel
- **Eat the frog** — identify your single most important move of the day
- **Today's tasks** — lightweight daily to-do list, auto-archives at midnight
- **3 gratefuls** — one line each
- **Mood** — pick an emoji from a dropdown; labels: amazing, good, calm, unsure, frustrated, low, tired, anxious
- **Feeling log** — tap "feeling log ↗" to open the analytics view:
  - 7-day trend: emoji row + score bars + weekly vibe summary. Tap any day to edit its mood
  - Monthly calendar: color-coded cells (green = positive, red = rough) with mood emoji per day, navigate by month

### Data & Settings (`···` menu)
- **+ add column** — add a new swim lane to the current board
- **↓ export cards** — export all boards and cards as a CSV (opens in Excel)
- **↓ export daily log** — export mood and gratitude history as a CSV
- **↑ import cards** — import a cards CSV to restore or bulk-add cards
- **Clear all** — wipe everything and start fresh
- All data lives in your **browser's localStorage** — no accounts, no servers

### Personalization
- **Dark mode** — toggle via the settings button (bottom right)
- **Background style** — choose from dot grid, lined, plain, or isometric grid
- Settings persist across sessions

### Design
- Dot-grid paper background (default)
- Caveat handwriting font for headers, Helvetica for card content
- Colored pencil-style left border accents on cards
- Responsive — works on desktop, tablet, and mobile

### PWA
- Install to home screen on iOS, Android, or desktop Chrome/Edge
- Works fully offline after first load
- Opens as a standalone app (no browser chrome)

---

## Getting Started

Open https://nikastashinsky.github.io/mindful-kanban/ in your browser. That's it — sample cards load on first visit.

**Install as an app:**
- **iOS**: Safari → Share → Add to Home Screen
- **Android**: Chrome → Menu → Install app
- **Desktop**: look for the install icon in the address bar

---

## Data & Privacy

- 100% local — nothing leaves your device
- No analytics, no tracking, no sign-in required
- Export your data as CSV anytime as a backup
- Import the CSV on any device to restore

---

## Files

| File | Purpose |
|------|---------|
| `index.html` | Entire app — CSS, HTML, and JS in one file |
| `manifest.json` | PWA metadata (name, icons, colors) |
| `service-worker.js` | Offline caching |

---

## Browser Support

| Browser | Support |
|---------|---------|
| Chrome / Edge | Full PWA |
| Firefox | Full |
| Safari (iOS 11.3+) | Partial PWA |
| Samsung Internet | Full |
