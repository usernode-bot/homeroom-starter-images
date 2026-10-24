# Game night times

> **Ready-made.** This repo was scaffolded by Homeroom as its ready-made
> **Game night times**. It works as it is; make it your own.

Find a time for game night: suggest a few times, everyone marks when they are free, and the best time rises to the top.

What it already does:

- **Suggest some times**: whoever starts a plan suggests two to eight, each a day and a time or a whole day, and anyone can suggest another while it is open.
- **Free, if needed, or can't**: everyone marks each time with one tap and can change it any time. The grid shows who is free when, and who in the project has not answered yet.
- **The best time rises**: the time the most people can make is named at the top, and whoever started the plan sets it, which closes the plan. Once its time has passed, a plan moves to Past.

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
