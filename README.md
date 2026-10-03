# Fanfare

Holding page for fanfare.

A single static `index.html` with no build step and no dependencies. Vercel
serves it as-is — no framework preset, no `vercel.json` needed.

## Files

| | |
| --- | --- |
| `index.html` | The page. Styles are inline so it renders in one request. |
| `favicon.svg` | The mark, on a rounded dark tile. |
| `og.png` | 1200×630 link preview for social and iMessage. |

## Domain

Live at `https://www.thefanfare.ca`. The apex (`thefanfare.ca`) 308-redirects to
`www`, which is why `www` is the canonical host in `index.html`.

## Local preview

Open `index.html` directly, or serve it if you want the absolute asset paths
(`/og.png`, `/favicon.svg`) to resolve the way they will in production:

```sh
python3 -m http.server 8000
```
