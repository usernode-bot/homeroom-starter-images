# Potluck planner

> **Ready-made.** This repo was scaffolded by Homeroom as its ready-made
> **Potluck planner**. It works as it is; make it your own.

Potlucks with a date and a place, who is bringing what by course (so the table is not six salads), and a chat for each one.

What it already does:

- **Plan a potluck**: a name, a date, a time and a place.
- **Who's bringing what**: say what you will bring and which course it is. Each course lists what is coming, and the courses nobody has taken yet are named.
- **Talk about it**: react to a dish, comment on it ("is it vegetarian?"), and chat with everyone coming.

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
