# Google Search Front-End Clone

This project recreates the front-end of Google Search using HTML and CSS. It includes:

- Regular Google Search (`index.html`)
- Google Image Search (`images.html`)
- Google Advanced Search (`advanced.html`)
- ## Styling

All pages use a shared stylesheet (`style.css`) to maintain consistent design. It includes:

- Centered layout and rounded search bar
- Styled buttons and input fields
- Navigation links in the top-right corner
- Blue "Advanced Search" button with white text

To apply the styles, each HTML file includes:

```html
<link rel="stylesheet" href="style.css">



## Features

- Centered search bar with rounded corners
- “Google Search” and “I’m Feeling Lucky” buttons
- Image search with `tbm=isch` parameter
- Advanced search with multiple query fields
- Navigation links between pages
- Styled to resemble Google’s aesthetics

## How It Works

Each form sends a GET request to Google’s servers using the appropriate parameters:
- `q` → search query
- `btnI` → “I’m Feeling Lucky”
- `tbm=isch` → image search
- `as_q`, `as_epq`, `as_oq`, `as_eq` → advanced search fields

## Setup

To run locally:
1. Clone the repo
2. Open `index.html` in your browser

No backend or dependencies required.

## License

MIT
