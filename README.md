# Book club times

> **Ready-made.** This repo was scaffolded by Homeroom as its ready-made
> **Book club times**. It works as it is; make it your own.

Find a weekly time for our book club: everyone marks the hours that work for them every week, and the time that suits the most people rises to the top.

What it already does:

- **Your week, once**: a grid of the days and the hours, 8 AM to 10 PM. Tap an hour that works for you every week, or hold and drag across several.
- **Everyone's week**: each hour is shaded by how many people can make it, and tapping one shows who can and who can't.
- **The best weekly time**: the hour that suits the most people is named at the top ("Tuesdays at 7 PM, 5 of 6 can make it"), with the next best and who still has to answer.

And what every Homeroom app gets:

- **Sign-in**: the server verifies the platform-issued user token (an
  RS256 JWT) on every request, so the app already knows who is using it.
- **Database**: the app has its own Postgres database. Its tables are
  created on boot by `api.js`.
- **Styling**: Tailwind CSS, precompiled by `npm run build` during image
  creation, following the platform's light or dark theme.

## Changing it

To change this app, ask Homeroom bot: open the app on Homeroom, tap the
Homeroom icon in the header, then **Suggest an improvement**, and describe
what you want in plain English. You can also run Claude Code against this repo directly; start with
`CLAUDE.md`, which carries the app-specific notes and points at the
platform rules.
