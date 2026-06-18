# Task Core Checklist

Task Core Checklist is a small local checklist web app inspired by a music-library style interface. It runs as a single HTML page and does not require a backend server.

## Features

- Add tasks directly in the browser.
- Delete individual tasks or clear the whole list.
- Check tasks during the current session.
- Save task text locally in the browser.
- Keep checked state temporary, so every new page load starts unchecked.
- Edit and save the checklist title.
- Show a completion message when all tasks are checked.
- Switch UI language between Chinese and English.
- Change the accent color theme.
- Save-and-close button that stores the current tasks and title before closing or showing a closed screen.
- Keep copied checklist files independent when they are opened from different paths.

## Usage

Open `index.html` in a browser.

No installation, build step, or backend service is required.

## Data Storage

Tasks, title, language choice, and theme choice are saved in `localStorage`.

Storage is scoped to the checklist file path. If you copy `checklist.html` or `index.html` to another folder or rename it, the copied file starts with its own separate checklist data in the same browser.

Checked task state is intentionally not saved. This keeps each checklist session fresh when the page is reopened.
