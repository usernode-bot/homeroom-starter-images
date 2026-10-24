# Grocery list

> **Ready-made.** This repo was scaffolded by Homeroom as its ready-made
> **Grocery list**. It works as it is; make it your own.

One shared grocery list that works like Homeroom's Todo List app: categories, ticked items kept in place, swipe actions, undo, search and due dates, and it opens and keeps working offline.

What it already does:

- **Categories**: items go in categories you make (aisles, shops, whatever suits), with a General part at the top for anything else. Press and hold an item to drag it within or between categories, and drag a category by its handle; fold a category away by tapping its name (a finished one starts folded).
- **Ticked in place**: ticking keeps an item's place, below the open items in its category with who ticked it. Swipe a row for Complete, Rename and Delete. "N done" hides or shows a category's ticked items, and the menu, which opens over the list, does it for the whole list.
- **Works offline**: the list opens with no connection from the copy saved on the phone, and adding, ticking, editing and deleting wait there until the connection is back, then sync. A line under the bar says when the list is offline or still syncing.
- **Undo, search and more**: undo and redo (Cmd/Ctrl+Z) for adding, deleting, editing, ticking and due dates; search as you type; pull down to refresh; optional due dates that sort the list; markdown export and import in Todo List's format; and the latest thing somebody else did, at the top.

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
