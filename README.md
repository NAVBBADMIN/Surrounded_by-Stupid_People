# Operations Field Manual — Behavioral Styles Book Club

6-week companion site for the team book club (Dr. Galanis, Michael, Casey, Alex, Derek, Clint, Jake), built around a Red/Yellow/Green/Blue behavioral-styles book.

## Files

| File | Week | Chapters | Focus |
|---|---|---|---|
| `index.html` | — | — | Hub page linking all six weeks |
| `week1.html` | 1 | 1–6 | Foundations & the Red profile |
| `week2.html` | 2 | 7–10 | The Yellow profile |
| `week3.html` | 3 | 11–13 | The Green profile |
| `week4.html` | 4 | 14–17 | The Blue profile |
| `week5.html` | 5 | 18–21 | Body language, perception & stress |
| `week6.html` | 6 | 22–29 | Feedback, group dynamics & workplace application |

Each week's page is fully self-contained (its own CSS/JS, no shared file dependency), so you can post them one at a time — no need to upload all six before week 1 goes live. `index.html` links to all six regardless of what's posted yet, so it's fine to push it on day one.

## Weekly checklist (before you post each file)

1. **Swap the Microsoft Forms link.** Open the week's file and search for `REPLACE-WITH-WEEK` — it's inside the button near the bottom (`Submit your Field Report`). Replace the placeholder URL with that week's real Forms link.
2. **Optional:** tweak the briefing text or interactive prompts if you want to fold in something specific from that week's discussion — everything is plain HTML/JS, no build step.
3. Commit and push the file to the repo (or upload directly via GitHub's web UI) the week it's assigned.
4. Share the `weekN.html` GitHub Pages link with the team the same way you did with the Patricia project.

## How it's built

- Static HTML/CSS/JS, no frameworks or build tools — works directly on GitHub Pages.
- Each week has a self-assessment and/or scenario/guessing interactive, all under 10 minutes.
- Self-assessment scores are saved to the browser's local storage on each person's own device only (nothing is transmitted anywhere) so that Week 6's composite view can pull together anyone's Weeks 1–4 scores automatically. This is a bonus feature, not a requirement — the page works fine even if someone skips a week or clears their browser.
- The real "record keeping" for the group is the Microsoft Form each week, same as before.

## Enabling GitHub Pages (if not already on)

Repo → Settings → Pages → Deploy from a branch → pick `main` (or wherever these files live) and `/ (root)` → Save. Your hub will be live at `https://<username>.github.io/<repo>/index.html`.
