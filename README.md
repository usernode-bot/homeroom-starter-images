# Steps challenge

> **Ready-made.** This repo was scaffolded by Homeroom as its ready-made
> **Steps challenge**. It works as it is; make it your own.

A monthly challenge: who logs the most steps, and how close the whole group gets to its goal together.

What it already does:

- **Log as you go**: anyone in the project adds the steps they did, today or another day this month, with a note if they like, and can take their own back.
- **A leaderboard and a group goal**: who has the most this month, how far everyone has got together, and where the group finishes at this pace. Anyone can change this month's goal; the next month starts with the usual one.
- **A fresh start every month**: "this month" is the calendar month where each person is. When a month ends its results stay, with a card to share on the next month's first days, and every past month can be looked at again.

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
