# BAND-MAID Instagram Archive

A searchable archive of translated BAND-MAID Instagram posts, hosted on GitHub Pages.

## Overview

This archive contains approximately 5,000 Instagram posts from BAND-MAID and its five members, spanning from 2014 to present. All posts include the original Japanese text alongside an English translation.

🔗 **View the archive here:**  
[https://drivetimebm.github.io/BAND-MAID_instagram/](https://drivetimebm.github.io/BAND-MAID_instagram/)

[Project Description (TBD)](https://www.reddit.com/r/BandMaid/tbd/)

## Features

- Full-text search across English translations and original Japanese text
- Filter by member (BAND-MAID, Saiki, Miku, Kanami, Akane, MISA)
- Date range filtering
- Links to original Instagram posts
- Virtual scrolling for smooth performance across the full dataset

## Files

| File | Description |
|---|---|
| `index.html` | Self-contained search interface |
| `instagram.json` | Archive data |
| `favicon.png` | Site favicon |

## Data Format

```json
[
  {
    "id": 1,
    "dateJST": "2014-09-30T16:48:59",
    "member": "Saiki",
    "jp": "ぷるぷる〜😌💞 #saiki #bandmaid #egg #purupuru",
    "en": "Puru puru~ 😌💞 #saiki #bandmaid #egg #purupuru",
    "url": "https://www.instagram.com/p/tj9UXgDYwJ/"
  }
]
```

| Field | Description |
|---|---|
| `id` | Sequential record ID |
| `dateJST` | Post datetime in Japan Standard Time (ISO 8601) |
| `member` | Posting member: `BAND-MAID`, `Saiki`, `Miku`, `Kanami`, `Akane`, or `MISA` |
| `jp` | Original Japanese caption |
| `en` | English translation |
| `url` | Link to the original Instagram post |

## Members

| Member | Color |
|---|---|
| BAND-MAID | White |
| Saiki | Blue |
| Miku | Pink |
| Kanami | Green |
| Akane | Gold |
| MISA | Purple |

## Related

- [BAND-MAID Tweet Archive](https://github.com/drivetimebm/BAND-MAID_tweets)
