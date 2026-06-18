# Internship Tracker

A simple, offline-first web app to log internship hours, visualize progress on a color-coded calendar, and print monthly reports.
[![Live Demo](https://img.shields.io/badge/Live_Demo-View_Here-4ade80?style=for-the-badge&logo=github&logoColor=white)](https://yraccoon.github.io/internship_tracker/)
[![GitHub Pages](https://img.shields.io/badge/Hosted_on-GitHub_Pages-black?style=for-the-badge&logo=github)](https://pages.github.com/)

## Features

- **Calendar View** – Visual monthly calendar with color-coded entries for Company, Holiday, Sick Leave, and School
- **Hour Tracking** – Add daily hours with descriptions, view cumulative totals per day
- **Progress Dashboard** – See completed hours, remaining hours, working days, and completion percentage at a glance
- **CSV Import/Export** – Backup or migrate your data easily
- **Print Reports** – Select any month range and print A4-optimized calendars
- **Local Storage** – All data stays in your browser, no server required

## Quick Start

1. Open `index.html` in any modern browser
2. Click on any date to add entries
3. Use Settings to set your required hours and start date
4. Export data via CSV or print monthly reports

## Tech Stack

- HTML5
- TailwindCSS (via CDN)
- Vanilla JavaScript
- Local Storage API

## Data Format

Exported CSV includes:
- Date (YYYY-MM-DD)
- Category (company/holiday/sick/school)
- Hours
- Description

