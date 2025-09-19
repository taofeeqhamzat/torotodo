# Toro Todo (Starter Project)

A Simple todo app for the codelab. Open `index.html` in your browser. No build tools, no server required.

## Features
- Add / edit / delete
- Toggle complete
- Filters (All / Active / Completed)
- JSON import/export
- Persists in `localStorage`

## Run
Just double-click `public/index.html`.

## Get started with the codelab 
***Open [codelab.md] (https://github.com/dftaiwo/torotodo/blob/main/codelab.md)***

## Designed Workshop Issues

### feat: Light and dark modes
Let's add the option for light and dark modes

### feat: Add due date & sorting
Add optional dueAt per todo (date input in UI).

Show due date in the list; add sort toggle (Created | Due Date | Completed).

Persist in localStorage while keeping backwards compatibility with existing data.

### feat: Filters & search
Add a text search box that filters by title (debounced).

Add a "Overdue" quick filter (dueAt < today && !completed).

### feat: CSV export
Add "Export CSV" button alongside JSON export.

CSV headers: id,title,completed,createdAt,dueAt.

Ensure values are properly escaped.


### pwa: Make it installable (manifest + service worker)
Convert the app to a Progressive Web App with offline capabilities


