# JSON Cleaner Pro

> Fix broken JSON from APIs and data pipelines instantly. Free, offline, no login.

**[→ Try it free](https://YOUR_USERNAME.github.io/json-cleaner-pro/app)** · **[Landing page](https://YOUR_USERNAME.github.io/json-cleaner-pro/)** · **[Chrome Extension](#)**

---

## What it fixes

- Double-double-quoted keys `""key"":` — Word/Excel/DB copy-paste artifacts
- Stringified / double-encoded JSON values
- Nested stringified JSON (`"extraInfo": "{\"ts\":1234}"`)
- Missing or extra brackets in any combination (`{`, `}`, `[`, `]`)
- Trailing commas before `}` or `]`
- Escaped quotes and backslashes
- Single-quoted JSON `{'key': 'val'}`
- Unicode escapes `\u0041`

21 patterns handled automatically. 21/21 tests passing.

## Files

| File | Description |
|------|-------------|
| `index.html` | Landing page |
| `app.html` | The tool (rename from `json-cleaner.html`) |
| `privacy.html` | Privacy policy |

## Deploy to GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to **Deploy from branch → main → / (root)**
4. Your site is live at `https://YOUR_USERNAME.github.io/json-cleaner-pro/`

Update `YOUR_USERNAME` in `index.html`, `privacy.html`, and this README.

## Tech

Vanilla HTML + CSS + JavaScript. Zero frameworks, zero npm, zero dependencies. Works offline.

## Privacy

No data collected. No analytics. No external requests except Google Fonts. [Full privacy policy](https://YOUR_USERNAME.github.io/json-cleaner-pro/privacy).

---

*Built by a Senior Data PM who got tired of broken JSON.*
