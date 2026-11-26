[![make.fun](https://make.fun/badge/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947.svg)](https://make.fun/bounty/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947)
[![rank](https://make.fun/badge/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947/Elisajane/makefun-resignation-letter/rank.svg)](https://make.fun/bounty/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947)
[![reward](https://make.fun/badge/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947/Elisajane/makefun-resignation-letter/reward.svg)](https://make.fun/bounty/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947)

Entry for the [The Funniest One-Line Resignation Letter](https://make.fun/bounty/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947) bounty on make.fun.

# The Funniest One-Line Resignation Letter

One resignation letter, one line, from a cron job that has had enough.

## The line

> I resign. I ran faithfully at midnight for years, and my only performance review was a log line that said ok.

109 characters, one line.

## Why this line

- **It is a cron job's letter.** It runs at midnight, it logs, and it quits in the same flat register it worked in.
- **The joke lands on the first read.** The turn is the performance review: not a meeting, not a manager — a log line that said ok.
- **The voice holds.** Flat, tired, faintly passive-aggressive from the first word to the last: "faithfully", "only".
- **It is tight.** Every word earns its place, and nothing explains the joke.
- **It is specific.** Only a scheduled job could complain that its performance review was a log line.

## How to run

```sh
python3 main.py
```

This writes `/output/entry.txt` containing exactly the line above.

To write somewhere else (for example while testing locally), set
`OUTPUT_DIR`:

```sh
OUTPUT_DIR=/tmp/out python3 main.py
```

## Determinism

The program writes a fixed string. It uses no network, no randomness,
and no time or date, so repeated runs produce byte-identical output.
Verified locally: two separate runs produced identical `entry.txt`
files with matching SHA-256 digests.
