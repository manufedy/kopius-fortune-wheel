# Kopius Fortune Wheel

A client-side "Spin the Wheel" web app with pre-configured prize stock limits.

## Prizes & Stock

| Prize | Stock |
|---|---|
| Sets de mate | 14 |
| Botellas | 14 |
| Soportes | 14 |
| Cuadernos | 6 |
| Mousepads | 14 |
| Mochilas | 7 |

When a prize runs out of stock, the wheel automatically re-spins. Once all 69 prizes are claimed, the spin button disables.

## Deploy to Netlify

1. Push this repo to GitHub.
2. Go to [app.netlify.com](https://app.netlify.com), click **Add new site → Import an existing project**.
3. Select the repo. No build command or output directory needed — `netlify.toml` handles it.
4. Click **Deploy site**.

Or drag-and-drop the project folder at [app.netlify.com/drop](https://app.netlify.com/drop).

## Deploy to Vercel

1. Push this repo to GitHub.
2. Go to [vercel.com/new](https://vercel.com/new), import the repo.
3. Framework Preset: **Other**. No build command needed.
4. Click **Deploy**.

## Local Preview

Open `index.html` directly in a browser, or serve it:

```bash
npx serve .
```
