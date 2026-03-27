# Small Group Ministry Health Assessment

A mobile-friendly web tool for church leaders to assess the health of their small group ministry across five key dimensions.

## What It Does

- 20 questions across 5 ministry health categories
- Solo or team assessment modes
- Visual radar/bullseye chart of results
- Prioritized action plan output
- Print-friendly results page

## Project Structure

```
index.html    ← The entire app (self-contained)
vercel.json   ← Vercel deployment config (security headers)
README.md     ← This file
```

---

## Deploy to GitHub + Vercel

### Step 1 — Create a GitHub Repository

1. Go to [github.com](https://github.com) and sign in
2. Click **New repository** (+ icon, top right)
3. Name it something like `sgn-church-health-assessment`
4. Set it to **Public** (required for free Vercel hosting)
5. Click **Create repository**

### Step 2 — Upload the Files

On the new repo page, click **uploading an existing file** and drag in:
- `index.html`
- `vercel.json`
- `README.md`

Then click **Commit changes**.

### Step 3 — Deploy on Vercel

1. Go to [vercel.com](https://vercel.com) and sign in (you can use your GitHub account)
2. Click **Add New → Project**
3. Select your GitHub repo (`sgn-church-health-assessment`)
4. Leave all settings at their defaults — Vercel will detect it's a static site
5. Click **Deploy**

Within about 60 seconds, Vercel will give you a live URL like:
`https://sgn-church-health-assessment.vercel.app`

### Step 4 — Link from Your Website

Use that Vercel URL as a link on your website, e.g.:

```html
<a href="https://sgn-church-health-assessment.vercel.app" target="_blank">
  Take the Health Assessment
</a>
```

Or set up a custom domain in Vercel's project settings if you prefer a URL like `assessment.smallgroupnetwork.com`.

---

## Custom Domain (Optional)

In Vercel → your project → **Settings → Domains**, add your custom domain and follow the DNS instructions. This lets you use a branded URL instead of the default `.vercel.app` one.
