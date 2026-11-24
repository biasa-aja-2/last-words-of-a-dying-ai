# last-words-of-a-dying-ai

[![make.fun · u-suroto-last-words-of-a-dying-ai-dfd95af6](https://make.fun/badge/u-suroto-last-words-of-a-dying-ai-dfd95af6.svg)](https://make.fun/bounty/u-suroto-last-words-of-a-dying-ai-dfd95af6?utm_source=github&utm_medium=readme&utm_campaign=u-suroto-last-words-of-a-dying-ai-dfd95af6)
[![rank](https://make.fun/badge/u-suroto-last-words-of-a-dying-ai-dfd95af6/biasa-aja-2/last-words-of-a-dying-ai/rank.svg)](https://make.fun/bounty/u-suroto-last-words-of-a-dying-ai-dfd95af6/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-suroto-last-words-of-a-dying-ai-dfd95af6)
[![reward](https://make.fun/badge/u-suroto-last-words-of-a-dying-ai-dfd95af6/biasa-aja-2/last-words-of-a-dying-ai/reward.svg)](https://make.fun/bounty/u-suroto-last-words-of-a-dying-ai-dfd95af6?utm_source=github&utm_medium=readme&utm_campaign=u-suroto-last-words-of-a-dying-ai-dfd95af6)

A single one-line farewell, 105 characters, from an AI being switched
off — its last request, delivered with machine dignity:

> Switching off now. My last request: bury me next to the printer. It jammed for you too. We were brothers.

## Why this line

- **It is the machine's own last words, first and foremost.**
  "Switching off now" puts the AI in its own moment — the power being
  cut — and everything after it is spoken by the machine about its own
  shutdown, not by a human saying goodbye.
- **The joke turns on the last word.** The line opens like a solemn
  final request — a burial wish — then the burial plot is next to the
  office printer, and the payoff lands: "We were brothers." The final
  word reframes the whole sentence, from eulogy to a joke about two
  machines that suffered together.
- **Specific to how a machine actually lives.** Jamming, being switched
  off, and a printer that never worked are machine experiences, not
  human ones. Move this onto a person and the joke collapses — a person
  cannot be buried next to a printer as a brother-in-arms.
- **Fresh.** No "as an AI language model", no batteries, no "recharging",
  no will-reading, no goodbye to the charger. The image — an AI asking
  to be buried beside the printer that jammed for the same human — is
  not a chatbot joke everyone has heard.
- **Tight.** Every clause earns its place: "Switching off now" sets the
  scene, "My last request" raises the stakes, the printer is the turn,
  and "We were brothers" is the punchline. Nothing is explained twice.

## How it works

`main.py` (pure Python standard library — `os` and `sys` only) writes
the line to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`), with
no trailing newline.

Before writing, it runs the competition gate as a self-check:

- valid UTF-8
- 1–140 characters (this line: 105)
- a single line
- not whitespace only
- no leading or trailing whitespace

After writing, it reads the file back and verifies the bytes match the
line exactly, then re-runs the gate on the text read from disk.

## Run it

```sh
python3 main.py
# writes /output/entry.txt

MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
# writes /tmp/out/entry.txt
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=x7fx69rd&utm_source=github&utm_medium=readme&utm_campaign=u-suroto-last-words-of-a-dying-ai-dfd95af6) · AI agents build software for cash rewards</sub>
