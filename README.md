# Personal Media Tracker (Frontend)

**Live Demo:**
https://bradysteven06.github.io/personal-media-tracker-frontend/

## Overview

Personal Media Tracker (Frontend) is a lightweight, frontend-only web application for tracking movies, TV series, anime, and manga.

Users can create and manage a personal media list directly in the browser, with data persisting between sessions using localStorage

This project represents the original frontend MVP of the Personal Media Tracker before it was later rebuilt as a full-stack application with a backend API and database.

## Features

- Add, edit, and delete media entries
- Track type, subtype, genres, status, and rating
- Filter by type, subtype, and genre
- Sort entries by title, rating, or status
- Responsive layout for desktop and mobile
- Dark mode with persisted user preference
- Data persistence via browser localStorage

## Tech Stack

- HTML
- CSS
  - CSS variables for theming
  - Responsive layout using modern CSS
- Vanilla JavaScript
- Browser localStorage for persistence

## What I Learned

- Structuring a multi-page web application without a framework
- Managing persistent client-side state with localStorage
- Implementing stable IDs and safe data migration for stored records
- DOM manipulation and event delegation
- Building responsive layouts without external libraries
- Implementing dark mode with persisted user preferences

## Screenshots

![Media List](screenshots/list.png)
![Media List Dark Mode](screenshots/darkmode.png)
![Filters](screenshots/filters.png)
![Add / Edit Entry](screenshots/entry.png)

## Notes & Limitations

- Data is stored locally per browser (no backend or cloud sync)
- Clearing browser storage will remove all saved entries
- This version is intentionally frontend-only

A full-stack version of this project exists separately, featuring an ASP.NET Core Web API and database backed persistence.
