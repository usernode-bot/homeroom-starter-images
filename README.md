# Study timer

> **Ready-made.** This repo was scaffolded by Homeroom as its ready-made
> **Study timer**. It works as it is; make it your own.

One big Start button for a 25 minute focus session, a gentle beep when it ends, and how many sessions you finished today.

What it already does:

- **One big button**: tap Start and a 25 minute session counts down; the big button becomes Pause, then Resume, with Reset beside it. The timer goes by the clock, so it still ends at the right time when the phone locks or the tab sits in the background.
- **A gentle beep**: two soft notes when the session is over, made by the browser itself. No sound file and nothing to turn on.
- **Today’s count**: how many sessions you finished today, and the minutes that makes. Yours alone, kept when you close the app, back to zero at midnight.

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
