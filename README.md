# Spending poll

> **Ready-made.** This repo was scaffolded by Homeroom as its ready-made
> **Spending poll**. It works as it is; make it your own.

The group's polls about what we spend on: anyone adds options, everyone votes, and each poll closes with a winner.

What it already does:

- **Ask the group**: anyone starts a poll with a question, a few options and when it closes (or when they close it).
- **Anyone adds options**: the group suggests more while the poll is open; the same option is not added twice.
- **Tick any, or pick one**: everyone ticks every option they would be happy with (most ticks wins), or a poll asks for one pick each. Secret votes show the totals, not who voted for what.
- **Decided**: a closed poll keeps its winner, so the group can see what it chose before.

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
