# Who's coming

> **Ready-made.** This repo was scaffolded by Homeroom as its ready-made
> **Who's coming**. It works as it is; make it your own.

An event everyone answers: going, maybe or can't, with a note, and the headcount at the top.

What it already does:

- **An event to answer**: a name, a day and a place.
- **Going, maybe or can't**: one tap each, with a note if you like ("+1", "bringing snacks").
- **The headcount**: how many are going, who might come, and who has not said yet.

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
