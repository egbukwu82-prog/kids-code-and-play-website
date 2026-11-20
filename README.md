# Kids Code and Play — website

The public website for **Kids Code and Play Club**, a registered Alberta non-profit offering free, live coding classes for kids ages 5–15.

**Build it. Break it. Fix it.**

## What's here

| File | Page |
|---|---|
| `index.html` | Home: programs, the weekly class, the coding challenge, FAQ, volunteer form |
| `support.html` | Support: growth plan, ways to give (Zeffy), funders and partners |
| `netlify.toml` | Tells Netlify there is no build step |

Each page is a single self-contained HTML file (styles and scripts inline). Fonts load from Google Fonts.

## Deploying

The site is hosted on Netlify and deploys automatically from the `main` branch. Any change pushed to `main` goes live within a minute.

- Build command: none
- Publish directory: `/` (repo root)

## Forms

The volunteer form on the home page uses **Netlify Forms** (`data-netlify="true"`). Form detection must be enabled in Netlify under **Forms**. Submissions appear there, and email notifications go to info@kidscodeandplay.org.

## Donations

Donate buttons link to Zeffy:
- Cohort 3 campaign ($5,000 by January 31, 2027)
- Monthly giving form (evergreen)

After January 31, point the main Donate buttons to the monthly form and remove the Cohort 3 wording on both pages.

## Contact

info@kidscodeandplay.org
