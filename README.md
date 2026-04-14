# JSON Cleaner Pro

> Fix broken JSON from APIs and data pipelines instantly. Free, offline, no login.

**[→ Try it free](https://YOUR_USERNAME.github.io/json-cleaner-pro/app)** · **[Landing page](https://YOUR_USERNAME.github.io/json-cleaner-pro/)** · **[Chrome Extension](#)**

---

## What it fixes

- Double-double-quoted keys `""key"":` — Word/Excel/DB copy-paste artifacts
- Stringified / double-encoded JSON values — expanded into real nested objects
- Unescaped inner quotes — `"name": "John "Danger" Doe"` → correctly escaped
- Embedded JSON strings with unescaped quotes — `"{ "key": "val" }"` → expanded object
- Missing or extra brackets in any combination (`{`, `}`, `[`, `]`)
- Arrays closed by wrong bracket — `[1, 2, 3,}` → `[1, 2, 3]`
- Windows file paths — `C:\users\john` → correctly escaped backslashes
- Literal newlines inside string values → escaped `\n`
- JS/Python values — `undefined`, `NaN`, `True`, `False`, `None`, `function(){}` → JSON equivalents
- Block and line comments — `/* ... */`, `//` → removed
- Invalid escape sequences — `\x41` → `A`, bare `\` → removed
- Unquoted keys and values — `{name: active}` → `{"name": "active"}`
- Double commas — `["a",,"b"]` → `["a","b"]`
- Trailing commas before `}` or `]`
- Single-quoted JSON — `{'key': 'val'}` → `{"key": "val"}`
- Unicode escapes — `\u0041` → `A`

**31 patterns handled automatically. 31/31 tests passing.**

---

## Files

| File | Description |
|------|-------------|
| `index.html` | Landing page with live before/after demo |
| `app.html` | The full JSON cleaning tool (v2.8 engine) |
| `privacy.html` | Privacy policy (required for Chrome Web Store) |
| `README.md` | This file |

---

## Deploy to GitHub Pages

1. Create a **public** GitHub repo named `json-cleaner-pro`
2. Upload all 4 files to the root of the `main` branch
3. Go to **Settings → Pages**
4. Set source to **Deploy from branch → main → / (root)**
5. Click Save — your site is live in ~60 seconds

**After deploy, replace `YOUR_USERNAME`** in `index.html`, `privacy.html`, and this README with your actual GitHub username.

Your URLs:
```
https://YOUR_USERNAME.github.io/json-cleaner-pro/          ← Landing page
https://YOUR_USERNAME.github.io/json-cleaner-pro/app       ← JSON tool
https://YOUR_USERNAME.github.io/json-cleaner-pro/privacy   ← Privacy policy
```

> ⚠️ **If you previously deployed an older version**, make sure to **replace all 4 files** — especially `app.html`. GitHub Pages serves whatever is in your repo; uploading only some files will leave the old engine in place for the others.

---

## Tech

Vanilla HTML + CSS + JavaScript. Zero frameworks, zero npm, zero dependencies. Works fully offline — all processing happens in your browser, nothing is sent to any server.

## Privacy

No data collected. No analytics. No external requests except Google Fonts. [Full privacy policy](https://YOUR_USERNAME.github.io/json-cleaner-pro/privacy).

---

*Built by someone who got tired of broken JSON. Engine v2.8 — 31/31 tests passing.*
