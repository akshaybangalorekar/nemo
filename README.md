# Nemo

A swim progression tracker for one swimmer at Glen Eira Leisure's swim school.

- **Now** — current level, days spent on it, the skills he is working on (tap to tick), and a button to move up.
- **Levels** — all nine levels with the skills each one requires, as published by Glen Eira Leisure.
- **History** — every level passed, with how long it took.

Everything is stored on the phone in `localStorage`. There is no account and no server; the passcode
(default `1981`) keeps a casual looker out, but it is not encryption — a determined person could read
the page and the stored data. Real per-child logins need a backend (Supabase or Cloudflare Workers),
which is the next step.

Level data comes from <https://www.geleisure.com.au/swim-school/class-levels>.
