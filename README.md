# Oxytocin — Landing Page

Marketing landing page for [Oxytocin](https://oxytocin.rahulgurung.com), a couples companion iOS app.

**Live site:** [oxytocin.rahulgurung.com](https://oxytocin.rahulgurung.com)

---

## About the App

Oxytocin is a minimal iOS app built around daily rituals that keep couples close — even when life gets busy. 3–5 minutes a day.

**Launching with:**
- **Daily Summary** — Record a voice note about your day. Your partner listens when they're ready.
- **Today's Question** — A daily prompt you both answer. See how your partner sees the world.
- **Date Planner** — Plan your next date together, intentionally.

More rituals on the way.

---

## Stack

Plain HTML + CSS — no framework, no build step. All fonts are bundled locally from the [Oxytocin Design System](https://github.com/rahgurung/oxytocin).

```
oxytocin-website/
├── index.html          # The whole site
├── fonts/              # DM Serif Display + DM Sans (local)
├── Oxytocin.png        # App icon
└── CNAME               # Custom domain config
```

**Design tokens** — from the Oxytocin design system:
| Token | Value | Role |
|-------|-------|------|
| Background | `#FDFAF6` | Warm cream |
| Primary | `#E8735A` | Terracotta |
| Secondary | `#7B9E87` | Sage green |
| Accent | `#F2C47E` | Warm gold |

---

## Local Development

No install needed — just open the file:

```bash
open index.html
```

Or serve it locally to avoid any font path quirks:

```bash
npx serve .
```

---

## Deployment

Deploys automatically to GitHub Pages on every push to `main` via GitHub Actions. The live URL updates within ~30 seconds of a push.

Custom domain is configured via the `CNAME` file pointing to `oxytocin.rahulgurung.com`.

---

## Related

- **iOS app repo:** [rahgurung/oxytocin](https://github.com/rahgurung/oxytocin) (private)
- **Portfolio:** [rahulgurung.com](https://rahulgurung.com)
