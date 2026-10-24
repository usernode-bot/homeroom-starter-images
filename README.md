# Chore list

> **Ready-made.** This repo was scaffolded by Homeroom as its ready-made
> **Chore list**. It works as it is; make it your own.

The group's chores, each always one person's or taking turns; turns move on every Monday.

What it already does:

- **Yours or taking turns**: a chore can always be one person's, or go round the project's members (the platform's member list, never just whoever opened the app), moving on every Monday (UTC). Tap a chore to change which.
- **Your turn**: the chores that are yours this week come first, with who is next.
- **Done this week**: anyone can tick a chore off, and the list says who did.

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
