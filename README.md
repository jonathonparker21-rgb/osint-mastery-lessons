# OSINT Mastery Lessons

Interactive, self-contained OSINT training course with randomized quizzes.

**Primary focus:** Practical tools and workflows for bail bondsmen and fugitive recovery / locating bail jumpers.

- All lessons are browser-based (no install needed)
- Randomized practice quizzes at the end of each lesson (retake as many times as you want)
- Auto-progress tracking (80%+ on quiz marks lesson complete and unlocks advanced content)
- Videos embedded for inline playback
- Tailored for Fedora KDE but works anywhere

## How to use

1. Open `index.html` directly in a browser for local use.
2. For best experience (videos play inline reliably + no errors), deploy it (see below).

## Deployment (recommended)

This site is designed to be hosted for easy access from any device.

- GitHub repo: (will be connected)
- Cloudflare Pages (free, fast HTTPS, excellent for static single-file sites)

## Local server (if opening file directly causes issues)

```bash
cd ~/Projects/osint-mastery-lessons
python3 -m http.server 8000
```

Then visit http://localhost:8000

## Notes for Bail Bondsman Work

The first lesson and several priority lessons are specifically structured around generating actionable leads for locating fugitives:
- Recent social / account activity
- Associate mapping
- Media metadata
- Reporting for bondsmen

See the "Bail Bondsman Fugitive Focus" sections throughout.

## Tech

- Single-file HTML (Tailwind via CDN + vanilla JS)
- Quizzes are fully client-side and randomized from question pools
- No backend, no data collection

Built for practical field use by investigators and skip tracers.

