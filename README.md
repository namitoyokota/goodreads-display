# Virtual Bookshelf

A simple static webpage that turns a Goodreads CSV export into a personal virtual bookshelf.

## Features
- Displays books from a Goodreads CSV export
- Separate shelves for Read, Currently reading, and Want to read
- Book covers from Open Library when available
- Shows ratings, authors, and reading dates
- Click a book to view its review and details
- Minimal, clean UI with no build process

## Setup

1. Export your library from Goodreads as a CSV file.
2. Rename the file to `export.csv`.
3. Place `export.csv` in the same directory as `index.html`.
4. Host the directory as a static website.

> The site needs to be hosted through a web server because browsers may block `export.csv` when opening `index.html` directly as a local file.

## Usage

Open the hosted site to view your bookshelf. The page automatically loads `export.csv` and organizes your books by their Goodreads shelf.

No configuration required.

## Disclaimer

This project was developed in hopes of learning how to "vibe code." I did not write a single line of code, nor have any idea what it does.
