# Lending library

> **Ready-made.** This repo was scaffolded by Homeroom as its ready-made
> **Lending library**. It works as it is; make it your own.

The things members can lend each other, who has each one now, and who has asked for it next.

What it already does:

- **Things to lend**: add something you can lend, with an optional note. It starts on your shelf.
- **Ask for it**: anyone can ask for a thing and joins the line; whoever has it hands it on to someone who asked.
- **Who has what**: each thing says who has had it since when. No due dates: its owner can always say it is back.

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
