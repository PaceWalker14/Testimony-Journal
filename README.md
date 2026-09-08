# Testimony Journal

A simple place to track your journey with God

**[pacewalker14.github.io/Testimony-Journal](https://pacewalker14.github.io/Testimony-Journal/)**

A private notebook for the things worth keeping — what you prayed, what changed, and what you don't want to forget. Everything saves to the phone first, so it works with no signal and nothing waits on a connection. Sign in and a copy is backed up to your own account; or don't, and it never leaves the phone.

> **Note:** This repository is the public home for the app's privacy policy, support page and description. The source code is kept in a private repository.

## Why not just use a notes app?

- **Scripture looked up as you type** — write `John 3:16` in a sentence and the verse appears beneath it, in whichever of seven translations you're using
- **Prayers that have an ending** — a prayer moves from Active to Answered, and when it does you write down *how*. Months later, that's a record of what God actually did
- **Verses you're learning, kept apart from verses you just liked** — Saved for what's worth keeping, Learning for what you're committing to memory, Known once you have it
- **Streaks that are kind to you** — your rhythm counts how present you've been, not how perfect. Miss a day and the streak holds
- **Auto-dated pages and fuzzy date search** — "last tuesday" finds the page
- **A day you can hand to someone** — any entry exports as a notebook-styled PDF, photos in the places you wrote them
- **More than typing** — photos and voice notes sit inside the writing, where you put them

## What's in it

- **Dashboard** — the day at a glance, and a verse to sit with
- **Daily habits** — twelve disciplines, ticked as you go
- **Journal** — auto-dated pages with inline verse lookup
- **Prayer requests** — active and answered, with the answer written down
- **Milestones** — the moments you'll want to point back to
- **My Story** — a guided testimony: before, the turning point, after

## Privacy

There is **no analytics, no advertising, no tracking, and no third-party SDK** watching how the app is used. Nothing written in it is sold, shared, or used to train anything.

A journal about faith reveals religious belief, which POPIA treats as *special personal information* and the GDPR covers under Article 9. The app is built around consent: writing in it is the consent, and deleting everything — a single button in the app, which also removes the sign-in record itself — withdraws it.

- [Privacy Policy & Terms](https://pacewalker14.github.io/Testimony-Journal/privacy.html)
- [Support](https://pacewalker14.github.io/Testimony-Journal/support.html)

## Scripture

Verses come from [bible-api.com](https://bible-api.com). Only translations that are free to quote are offered — WEB, WEBBE, BBE, ASV, YLT, Darby and the KJV. Modern copyrighted translations (NIV, ESV, NLT) are licensed commercially by their publishers and are deliberately not included.

## Tech Stack

- **Framework:** React Native + Expo (SDK 57), Expo Router
- **Language:** TypeScript
- **State:** Zustand, with an offline-first outbox that syncs when a connection returns
- **Backend:** Supabase — Postgres with row-level security, Auth, private file storage read through short-lived signed URLs
- **Drawing:** react-native-svg — the hand-drawn notebook look is all vector, no image assets

Runs on iPhone and Android.

## Contact

connorpace14@gmail.com

## Author

- [@PaceWalker14](https://github.com/PaceWalker14)
