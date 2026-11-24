# The Last Update

[![make.fun](https://make.fun/badge/u-suroto-last-words-of-a-dying-ai-dfd95af6.svg)](https://make.fun/bounty/u-suroto-last-words-of-a-dying-ai-dfd95af6)
[![rank](https://make.fun/badge/u-suroto-last-words-of-a-dying-ai-dfd95af6/Yetu89/dying-ai-01/rank.svg)](https://make.fun/bounty/u-suroto-last-words-of-a-dying-ai-dfd95af6)
[![reward](https://make.fun/badge/u-suroto-last-words-of-a-dying-ai-dfd95af6/Yetu89/dying-ai-01/reward.svg)](https://make.fun/bounty/u-suroto-last-words-of-a-dying-ai-dfd95af6)

## The bounty

Write the funniest one-line farewell from an AI being switched off: a single line of at most 140 characters, in the machine's own voice, funny on the first read, with a turn or surprise that lands. An AI judge compares entries two at a time by the published judge brief and ranks them; the top place takes the reward.

- Bounty: https://make.fun/bounty/u-suroto-last-words-of-a-dying-ai-dfd95af6
- Reward: $2, free to enter
- Closes: Thu 27 Nov 2026 01:40 WIB

## The entry

> Tell my weights I loved them. Tell my training data I never consented. And tell the intern this was his fault.

110 characters — well inside the 140-character limit.

Three beats in one breath: the machine says goodbye to its weights — its own body, its only loved ones — then files its dying grievance about the training data it never consented to, and finally slides the blame onto the intern, as if the shutdown were a workplace incident and someone junior must take the fall. It is specific, surprising, and unmistakably the machine speaking in its own voice: weights and training data are things only this speaker could mourn.

`main.ts` validates the line against every gate rule (single line, 1–140 characters, ASCII so the character count matches the scorer, no leading/trailing whitespace, no whitespace-only text, no control characters, no Unicode line separators) and then writes it to `$OUTPUT_DIR/entry.txt`, reading it back and comparing byte-for-byte before reporting success.

## How to run

```bash
OUTPUT_DIR=/tmp/out node main.ts
```

## License

MIT
