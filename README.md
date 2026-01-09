# Little Calendar

A simple desktop calendar app built with HTML, CSS, JavaScript, and ElectronJS. This project is a part of my YouTube tutorial series on building your first Electron application. 

## Tutorial video

I posted a full YouTube tutorial walking through how to build this step-by-step from scratch, so this repo provides the code along the way.

See Youtube video:

## Design File

Figma design file for this project: https://www.figma.com/design/iYQcS1Wk1f83vyh8ETsH8w/Little-Calendar?node-id=0-1&p=f

## What's in this repo

| File / Folder | Purpose |
| --- | --- |
| `index.html` | The main HTML layout for the calendar UI |
| `styles.css` | All styles for the calendar interface |
| `script.js` | Frontend JavaScript controlling calendar logic |
| `main.js` | Electron main process — creates the desktop window and loads your UI |
| `package.json` | Project metadata & dependencies |
| `.gitignore` | Files and folders ignored by Git |
| `assets/` | Images, icons, and other static assets |
| `package-lock.json` | Auto-generated lock file for dependencies |

## How to use

### 1. Clone This Repo

```
git clone https://github.com/nasha-wanich/little-calendar.git
cd little-calendar
```

### 2. Install Node.js

Make sure you have Node.js installed, then run:

```
npm install
```

This installs Electron and any other modules required to run the app.

### 3. Run the App Locally

'''bash
npm run start
'''

This will open your Little Calendar as a desktop application powered by Electron.