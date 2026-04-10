# Wins Tracker App

A personal monthly wins tracker for logging earnings, setting goals, and visualizing income sources — built with zero build tools.

## Demo

**[Open Wins-Tracker-App](https://wins-tracker-app.vercel.app/)**

## Features

- Log monthly wins with project name, amount, and source category
- Set monthly earning goals with progress bars
- 5 chart types: Bar, Line, Area, Radar, Pie
- Source breakdown with yearly/monthly views
- Custom source categories (add/remove your own)
- Dark / Light theme toggle
- CSV Import & Export (clipboard, file download, file upload)
- All data saved locally in your browser via `localStorage`
- Switch devices by exporting CSV from one and importing on another
- Year navigation to track across multiple years
- Reset controls for individual months or full year
- Fully responsive — works on mobile and desktop

## Project Structure

```
Wins-Tracker-App/
├── index.html    # The entire app (single file)
├── demo.html     # Demo version with sample data
├── README.md
└── LICENSE
```

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Ollie202/Wins-Tracker-App.git
   ```
2. Open `index.html` in your browser.

No npm, no Vite, no build step. Just open the file.

## CSV Format

**Wins:**
```
Year,Month,Project,Amount,Source
2026,Jan,My Bounty,100,Bounties
2026,Feb,Content Deal,50,Content
```

**Goals:**
```
GOAL,Year,Month,Target
GOAL,2026,Jan,500
GOAL,2026,Feb,400
```

Export from one device, import on another — your data travels with you.

## Built With

- Vanilla JavaScript (no frameworks)
- Chart.js (via CDN)
- Browser `localStorage` for data persistence

## License

This project is open source and available under the [MIT License](LICENSE).
