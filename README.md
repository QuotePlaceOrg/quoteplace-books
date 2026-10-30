# quoteplace-books
Book data for QuotePlace — notable books by each author, powering Books-by sections on author pages.

## Data layout

- `books.json` — index: counts, file list, and field schema.
- `books-data/part-01.json` … `part-07.json` — the full dataset: 4,272 books by 929 QuotePlace authors, extracted from Open Library on 2026-10-30 (up to 5 best-known books per author, ranked by Open Library edition count, with a manual curation pass).
- Each entry: author, title, year, editions, cover_id, ol (Open Library path), amazon_url (to be filled with affiliate links).
