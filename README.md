# Apple Website Clone

A front-end clone of the Apple homepage built with plain HTML, CSS, and JavaScript. The project replicates Apple's hero banner design, featuring full-width product banners for the MacBook Pro 16-inch, iPhone 11 Pro, and iPhone 11.

## Features

- Responsive hero banners with full-bleed background images
- Apple-style typography, layout, and link colors
- Light/dark text variants per banner (white text on dark images, dark text on light images)
- Mobile-friendly layout via CSS media queries

## Project Structure

```
appleClone/
├── index.html        # Main HTML entry point
├── style.css         # Global and banner styles
├── js/
│   └── script.js     # JavaScript (in progress)
└── images/
    ├── macbook-pro-16.jpg
    ├── iphone-11-pro.jpg
    └── iphone-11.jpg
```

## Getting Started

No build tools or dependencies are required — this is a static site.

### Run locally

1. Clone the repository:

   ```bash
   git clone https://github.com/DawitMahabaw/appleClone.git
   cd appleClone
   ```

2. Open `index.html` in your browser:
   - **Double-click** `index.html` in your file explorer, or
   - Use the **Live Server** extension in VS Code (right-click `index.html` → _Open with Live Server_)

That's it — no `npm install`, no build step.

## Branches

| Branch         | Description                                 |
| -------------- | ------------------------------------------- |
| `master`       | Stable base                                 |
| `hero-banners` | Active development — hero banner components |
| `and others`   |

## Contributing

1. Create a feature branch off `hero-banners`.
2. Make your changes and open a pull request against `hero-banners`.
3. Follow the existing CSS class naming convention (`banner`, `banner-bg`, `banner-content`, etc.).

## Credits

Built as a Phase 3 / Week 14 project at [Evangadi Tech](https://www.evangadi.com/).
