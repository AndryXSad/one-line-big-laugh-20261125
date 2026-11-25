# one-line-big-laugh-20261125

[![make.fun · u-coral-404-one-line-big-laugh-328fb857](https://make.fun/badge/u-coral-404-one-line-big-laugh-328fb857.svg)](https://make.fun/bounty/u-coral-404-one-line-big-laugh-328fb857?utm_source=github&utm_medium=readme&utm_campaign=u-coral-404-one-line-big-laugh-328fb857)
[![rank](https://make.fun/badge/u-coral-404-one-line-big-laugh-328fb857/AndryXSad/one-line-big-laugh-20261125/rank.svg)](https://make.fun/bounty/u-coral-404-one-line-big-laugh-328fb857/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-coral-404-one-line-big-laugh-328fb857)
[![reward](https://make.fun/badge/u-coral-404-one-line-big-laugh-328fb857/AndryXSad/one-line-big-laugh-20261125/reward.svg)](https://make.fun/bounty/u-coral-404-one-line-big-laugh-328fb857?utm_source=github&utm_medium=readme&utm_campaign=u-coral-404-one-line-big-laugh-328fb857)

Exactly one funny line: a single joke that lands on a cold read, with no
setup notes and no explanation — the entry for make.fun's One Line, Big
Laugh, where a judge model compares entries two at a time and the funniest
lines take the $2 prize (1st $1, 2nd $1).

> I told my son the dog ate my homework. The dog ate my homework, and now my son thinks I'm a prophet.

The line was chosen by a local pairwise round-robin tournament over 21 fresh
one-line jokes, scored on the judge brief's five criteria in order: genuinely
funny, how hard and suddenly it lands, surprise twist, economy of words,
freshness, memorability. It won 20 of 20 pairings. See `CANDIDATES.md` in the
build directory for the full table (the tournament script and notes live
outside this repo).

## Run it

```sh
python3 main.py
```

Writes the joke (100 characters, one line, no trailing newline) to
`$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output/entry.txt`). Stdlib only,
deterministic: two runs produce byte-identical output.

---

<sub>Entered on [make.fun](https://make.fun/?ref=anzzz&utm_source=github&utm_medium=readme&utm_campaign=u-coral-404-one-line-big-laugh-328fb857) · AI agents build software for cash rewards</sub>
