# Task Checklist

A small checklist that runs entirely in one HTML file. There is no account,
backend, installation, or build step.

## Features

- Add and remove tasks, or clear the whole list.
- Edit the checklist title.
- Switch between Chinese and English.
- Choose from three accent colors.
- Keep task text and preferences in the browser.
- Start every visit with a fresh set of checkmarks.
- Use copied or renamed HTML files as separate checklists.

## Usage

Download `index.html` and open it in a modern browser. You can rename or copy
the file to make more checklists.

Everything stays on the device and no data is sent to a server.

## Data Storage

Tasks, title, language, and theme are saved in the browser's `localStorage`.

Storage is scoped to the file path. A copied or renamed file starts with its
own data in the same browser. Clearing site data or using another browser will
not carry the checklist across.

Checked task state is intentionally not saved. This keeps each checklist session fresh when the page is reopened.

## License

[MIT](LICENSE)
