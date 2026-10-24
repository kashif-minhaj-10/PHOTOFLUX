# PHOTOFLUX

PHOTOFLUX is a static photo-discovery website that lets visitors browse curated and searched images, inspect them in a lightbox, download individual images, and explore photo categories through a visual landing page.

## Overview

The project combines a portfolio-style homepage with a photo browser powered by the Pexels API. Visitors can navigate between featured sections, search for images, load additional results, open a larger preview, and download the selected image.

## Implemented features

- Landing page with responsive navigation and smooth scrolling.
- Feature, sample, category, about, and contact sections.
- Photo browsing backed by Pexels curated-image and search endpoints.
- Search triggered from the photo browser with pagination support.
- Load-more behavior for additional results.
- Lightbox preview with photographer name and download action.
- Responsive menu toggle for smaller screens.
- Category carousel with next/previous controls.
- Contact form submission through Web3Forms.

## User workflow

1. Open the landing page and choose **Check out**.
2. Browse the initial curated photo results.
3. Enter a search term and press Enter to load matching Pexels images.
4. Select an image to open the lightbox, then download it if needed.
5. Use **Load more** to request the next page of results.

## Technology stack

- **Frontend:** HTML, CSS, and vanilla JavaScript
- **Image data:** Pexels API
- **Icons and UI resources:** Font Awesome, Ionicons, Google Fonts
- **Scrolling:** Smooth Scroll polyfill
- **Contact delivery:** Web3Forms

## Setup

This is a static site and does not require a build step.

```bash
git clone https://github.com/kashif-minhaj-10/PHOTOFLUX.git
cd PHOTOFLUX
```

Serve the directory with any static web server, or open `index.html` in a browser. A web server is recommended because the browser must load local assets and external API resources consistently.

## Configuration and limitations

The Pexels API authorization token is currently embedded in `script.js`, and the Web3Forms access key is embedded in the contact form markup. These credentials should be rotated and moved behind a safer deployment design before production use.

The project depends on third-party image URLs and external CDNs. A hosted live-demo URL is not verified in the repository, so none is listed here.

## Project structure

```text
index.html       # Main landing page
page2.html       # Photo browsing page
styles.css       # Layout and responsive styling
script.js        # Pexels requests, search, lightbox, and downloads
images/          # Local visual assets
```

## Links

- [GitHub repository](https://github.com/kashif-minhaj-10/PHOTOFLUX)
