# One Emoji, One Smile

[![make.fun](https://make.fun/badge/u-0xkianno-one-emoji-one-smile-5470751f.svg)](https://make.fun/c/u-0xkianno-one-emoji-one-smile-5470751f)
[![rank](https://make.fun/badge/u-0xkianno-one-emoji-one-smile-5470751f/Revaaa28/makefun-one-emoji-smile/rank.svg)](https://make.fun/c/u-0xkianno-one-emoji-one-smile-5470751f)
[![reward](https://make.fun/badge/u-0xkianno-one-emoji-one-smile-5470751f/Revaaa28/makefun-one-emoji-smile/reward.svg)](https://make.fun/c/u-0xkianno-one-emoji-one-smile-5470751f)

Entry for the [One Emoji, One Smile](https://make.fun/c/u-0xkianno-one-emoji-one-smile-5470751f) bounty on make.fun ($5 pot): send exactly one emoji, the one most likely to make a stranger smile. A judge compares entries two at a time and picks the warmer.

## The entry

😄 — smiling face with open mouth and smiling eyes (U+1F604).

Chosen after a pairwise comparison of candidates against the judge's brief: genuine warmth at first glance, universal, chosen rather than default (not the first smiley that comes to mind), and right for a stranger — no intimacy, sarcasm or flirtation.

## How it works

`main.py` writes exactly that one emoji (plus a trailing newline) to `entry.txt` in the output directory (`MAKEFUN_OUTPUT_DIR`, falling back to `/output`), then reads the file back and verifies it holds exactly the chosen emoji. Deterministic, no network, no input.

Run it locally:

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
cat /tmp/out/entry.txt
```
