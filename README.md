# Gorge Access — Web Embeds

Self-contained HTML embeds for [gorgeaccess.org](https://www.gorgeaccess.org), hosted via GitHub Pages.

## Embeds

| File | Purpose | Live URL |
|------|---------|----------|
| `clinic-finder.html` | Step-by-step abortion options finder (pre-appointment → pills by mail → in-clinic map), bilingual EN/ES, points to ineedana.com for verified availability | https://kate-rose.github.io/gorgeaccess-embeds/clinic-finder.html |

## How to embed in Squarespace

Add a **Code Block** to a page and paste:

```html
<iframe
  src="https://kate-rose.github.io/gorgeaccess-embeds/clinic-finder.html"
  style="width:100%; max-width:780px; height:2200px; border:none; display:block; margin:0 auto;"
  title="Finding Abortion Care in the Gorge"
  loading="lazy">
</iframe>
```

## Notes

- The clinic finder includes a built-in English/Español toggle. It **auto-hides** if [Weglot](https://weglot.com/) is detected on the page, so it won't conflict if you add site-wide translation later. (Note: Weglot cannot translate inside an iframe — use the built-in toggle for iframe embeds.)
- All clinic data (cities, drive times) is hardcoded in the file for easy editing. Real-time availability is intentionally delegated to ineedana.com.
