# THERMOTWIN — Wellbore Sentry

A static, interactive technical-flow demonstration using local synthetic data. It has no build step, package installation, server functions, or live industrial connections.

## Run locally

Open `index.html` directly, or run a local static server from this folder:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy to Vercel

Deploy this `outputs` folder as the project root. It contains `index.html` and `vercel.json` at its root.

In Vercel, use the **Other** framework preset, leave the Build Command blank, and use `.` as the Output Directory. No dependencies or environment variables are required. You can also deploy from this folder with the Vercel CLI:

```sh
vercel
```

The site is static HTML, CSS, and JavaScript. Every displayed measurement and scenario is illustrative synthetic data. The approval controls only update the local demonstration interface.
