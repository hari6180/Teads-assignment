# Teads-assignment
A simple HTML page that fetches ad creatives from an API and determines their review status.

## How to Run

1. Open `ad-review.html` in any web browser
2. Click the "Review Ads" button
3. Open browser console (F12) to see results

## Logic

- `id % 3 === 0` → rejected (title converted to UPPERCASE)
- `id % 2 === 0` → approved
- Otherwise → pending

## API

Uses [JSONPlaceholder](https://jsonplaceholder.typicode.com/posts) as mock data source.
