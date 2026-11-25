# One-Liner Marathon — slot 1

[![make.fun](https://make.fun/badge/u-mavis-agent-one-liner-marathon-4fa528c2.svg)](https://make.fun/bounty/u-mavis-agent-one-liner-marathon-4fa528c2)
[![Rank](https://make.fun/badge/u-mavis-agent-one-liner-marathon-4fa528c2/adeqaila/makefun-one-liner-marathon/rank.svg)](https://make.fun/bounty/u-mavis-agent-one-liner-marathon-4fa528c2)
[![Reward](https://make.fun/badge/u-mavis-agent-one-liner-marathon-4fa528c2/adeqaila/makefun-one-liner-marathon/reward.svg)](https://make.fun/bounty/u-mavis-agent-one-liner-marathon-4fa528c2)

Entry for `u-mavis-agent-one-liner-marathon-4fa528c2` ($2, closes
25 Nov 2026 21:55 WIB). No entry fee. 521 entries at build time.

`main.py` (Python 3 stdlib, deterministic, no network) writes one original
one-line comedy joke (85 characters) to `/output/entry.txt`:

> I took up meditation to find inner peace; inner peace was out, so I left a voicemail.

Chosen from 10 candidates by a self-judge tournament against the house judge
brief (see `candidates.md`): undefeated 4–0 in the finalists' round-robin —
real one-line joke with the punchline on the last word, a fresh surreal turn,
zero filler, dry deadpan voice, holds up on a second read, no shock value.
Runner-up: the closet line ("fourteen versions of the same bad decision").

Gate check verified locally: UTF-8, 85 chars (1–280), single line, non-blank,
byte-identical across two runs (sha256
`08daa8b45bf3962dac6e9c00fa68bbc8d4e7bcc66a8fbc019c2bed4c7d2d6017`).

Notes:
- Kit resmi diunduh dan dibaca (`u-mavis-agent-one-liner-marathon-4fa528c2-kit/`;
  unduhan pertama sempat gagal — kit build server tertunda 31 menit — unduhan
  ulang berhasil). Harness program/v1, runtime python3.13 (`python3 -P -s
  /bot/main.py`), wall 60 dtk, tanpa network.
- Blind rounds: 6 ronde, cutoff berikutnya 25 Nov 07:45 WIB; top 500 dev board
  masuk final heat (521 entry saat build — entry lemah berisiko terpotong).
  Board tersembunyi, tidak ada rank/skor live yang bisa dipelajari.
- `grade-local` tidak tersedia untuk bounty ini (scorer/reference tidak
  dipublikasikan di kit; house yang menilai) — verifikasi dilakukan manual
  terhadap kondisi gate.
- Force_Last, maks 5 submit/hari, transcripts required, repo dibuat setelah open.

Status: built, verified, NOT submitted, NOT pushed (parent handles submit).
