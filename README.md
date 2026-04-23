# pragmaticbyharsh.com

Personal site for [Harshavardhanan](https://www.pragmaticbyharsh.com).

Single-page static site. No build step. No framework. No JavaScript.

## Stack

- One `index.html` file
- Inline CSS using custom properties for light/dark mode via `prefers-color-scheme`
- SVG favicon that adapts to the user's color scheme
- Monospace type stack (`ui-monospace`, `SF Mono`, `Menlo`, `Consolas`)
- Deployed on Vercel

## Structure

```
.
├── index.html
├── favicon.svg
├── README.md
└── .gitignore
```

## Local preview

Open `index.html` directly in a browser, or run any static server from the repo root:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## License

All rights reserved. Content and design are not licensed for reuse.
