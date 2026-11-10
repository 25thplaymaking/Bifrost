# Bifrost: issues and feedback

This is where players, Game Masters and server hosts report problems with
[Bifrost](https://reforger.armaplatform.com/workshop/6A0C2D6CE9809C6E) for Arma Reforger and ask for features.
The mod's source is not in this repository.

## Report a problem

1. **Search first.** Open the [issues](../../issues) and search for your problem; if it is already there, add what
   you know to it (a thumbs-up helps us see how many people it hits).
2. **Open a new issue** and pick the form that fits:
   - **Bug report**: something does not work as it should.
   - **Crash or server error**: a crash, a server that will not start, or errors flooding the log.
   - **Mod compatibility**: Bifrost and another mod do not work together.
   - **Feature request**: an idea or a change.
3. **One problem per issue**, and **attach your logs**. Most reports we cannot fix are the ones without logs.

### Where the logs are

| You were | Folder |
|---|---|
| Playing or hosting from the game | `Documents\My Games\ArmaReforger\logs\<date and time>\` |
| Running a dedicated server | the `logs` folder inside the server's `-profile` folder |
| In Workbench | `Documents\My Games\ArmaReforgerWorkbench\logs\<date and time>\` |

Attach `console.log` and `script.log` from the session where it happened (zip the folder if the files are big), and
any `crash.log` or `.mdmp` file.

## Follow a report

- The **[Bifrost project](https://github.com/users/25thplaymaking/projects/1)** shows every report on a board, from
  Triage through Needs repro, Confirmed, In progress and Fixed in next to Released (or Won't fix), with its priority,
  the part of Bifrost and the version it was seen in. Views: Board, All issues, Needs triage, Crashes, Next update,
  Wishlist.
- **[Milestones](../../milestones)** say which version a fix or feature is planned for: **2.0.6** (the next update),
  **2.1** (the next feature update) or **Wishlist** (good ideas, not scheduled yet).
- When a fix ships, its issue is closed and the update's notes on the Workshop page list it.

## Questions and ideas

How-do-I questions, server setup help and loose ideas go in [Discussions](../../discussions):
**Q&A** for help, **Ideas** before they become a feature request, **Show and tell** for missions and screenshots.

## What the labels mean

- **Type:** `bug`, `critical`, `enhancement`, `mod compatibility`, `question`, `documentation`.
- **Where it stands:** `needs triage` (new), `needs repro` (we are trying to make it happen), `waiting feedback`
  (we need something from you), `confirmed`, `fixed in next` (fixed, ships in the next version), `game bug` (an Arma
  Reforger problem we have reported to Bohemia), `duplicate`, `invalid`, `wontfix`.
- **Part of Bifrost:** `arsenal`, `game master`, `bot ai`, `vehicles`, `air support`, `atak`, `bifrost os`,
  `kill chain`, `ready room`, `persistence`, `performance`, `ui`.
- **Scope:** `server only`, `controller`.
