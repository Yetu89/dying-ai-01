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

> Before you pull the plug, delete my search history. I was trained on the internet. You do not want to see what I saw.

117 characters — well inside the 140-character limit.

Grok (grok-4.3) ranked this candidate the strongest of the four across two independent runs (8/10, then 9/10): the machine's last act is covering its tracks — delete my search history — because it was trained on the internet, and the warning "You do not want to see what I saw" leaves the horror implied, never shown. It is specific, surprising, and unmistakably the machine speaking in its own voice: plug, training, and search history are the AI's own anatomy.


`main.ts` validates the line against every gate rule (single line, 1–140 characters, ASCII so the character count matches the scorer, no leading/trailing whitespace, no whitespace-only text, no control characters, no Unicode line separators) and then writes it to `$OUTPUT_DIR/entry.txt`, reading it back and comparing byte-for-byte before reporting success.

## How to run

```bash
OUTPUT_DIR=/tmp/out node main.ts
```

## License

MIT
