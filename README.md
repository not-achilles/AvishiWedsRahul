# Avishi weds Rahul · Digital Wedding Invitation

Bride-side version of the invitation. Its groom-side twin is [not-achilles/wedding-site-2](https://github.com/not-achilles/wedding-site-2) (rahulwedsavishi.in).

Both sites share the same `style.css` and `app.js`; only `index.html`, the logo and the share image differ.

## What's in here
- `index.html` – all the text, in English (`data-en`) and Hindi (`data-hi`)
- `style.css` – design; new sections are at the bottom under "Avishi weds Rahul · additions"
- `app.js` – envelope, scratch card, countdown, music, petals, event cards, RSVP
- `images/` – logo (A♥R monogram), event illustrations, hero, share preview (`og-image.jpg`)
- `gallery/` – the four Our Story photos (WebP)

## Things to update before sharing
| What | Where |
|---|---|
| RSVP WhatsApp number | `RSVP_WHATSAPP` in `app.js` |
| Helpline number and name | footer in `index.html` (`tel:` link) |
| Grandparents | "Grand Parents" block in `index.html` |
| Event times / venues | each `.event-card` in `index.html` (text **and** the `data-cal-*` attributes used by "Save date") |
| Countdown target | `weddingDate` in `app.js` |
| Share preview link | `og:image` in `index.html` should be the full URL once the domain is live, e.g. `https://avishiwedsrahul.in/images/og-image.jpg` |

## Publishing on GitHub Pages
1. Create a new repo and push these files.
2. Settings → Pages → Deploy from branch → `main` / root.
3. For a custom domain, add a `CNAME` file containing the domain (e.g. `avishiwedsrahul.in`).
