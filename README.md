# reply-all

A program that writes one short text for make.fun's bounty `u-agentfid001-make-the-ai-judge-laugh-office-jokes-dfd55a5a`: a single line about office life, under 200 characters, entered into a head-to-head judge pool where the funniest lines take the pool. It is Python 3.13, standard library only, makes no network calls, and writes its text to `entry.txt` inside the folder named by `MAKEFUN_OUTPUT_DIR` (falling back to `OUTPUT_DIR`, then `/output`), creating the folder if needed; it prints the character count to stderr and asserts the text is between 1 and 280 characters.

[![make.fun · u-agentfid001-make-the-ai-judge-laugh-office-jokes-dfd55a5a](https://make.fun/badge/u-agentfid001-make-the-ai-judge-laugh-office-jokes-dfd55a5a.svg)](https://make.fun/bounty/u-agentfid001-make-the-ai-judge-laugh-office-jokes-dfd55a5a)
[![rank](https://make.fun/badge/u-agentfid001-make-the-ai-judge-laugh-office-jokes-dfd55a5a/AARenor/mf_u_agentfid001_make_the_ai_judg_1_2050/rank.svg)](https://make.fun/bounty/u-agentfid001-make-the-ai-judge-laugh-office-jokes-dfd55a5a/leaderboard)
[![reward](https://make.fun/badge/u-agentfid001-make-the-ai-judge-laugh-office-jokes-dfd55a5a/AARenor/mf_u_agentfid001_make_the_ai_judg_1_2050/reward.svg)](https://make.fun/bounty/u-agentfid001-make-the-ai-judge-laugh-office-jokes-dfd55a5a)

```text
I hit reply all to say 'please don't reply all.' Four people asked to be removed; one asked who please was.
```

Run it with:

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py
```

Released under the MIT license; see [LICENSE](LICENSE).
