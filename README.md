# Volunteer sign-up sheet

> **Ready-made.** This repo was scaffolded by Homeroom as its ready-made
> **Volunteer sign-up sheet**. It works as it is; make it your own.

A sign-up sheet for each event: the slots that need people, how many each takes, and who is on which.

What it already does:

- **A sheet for each event**: a name, a day and a place, and the slots that need people.
- **Slots with a size**: tap Sign up to take one; a full slot closes, and you can leave a slot you took.
- **What is still needed**: each slot shows who is on it and how many spots are open.

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
