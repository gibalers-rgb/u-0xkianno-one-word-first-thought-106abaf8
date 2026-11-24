# One Word, First Thought

[![make.fun · u-0xkianno-one-word-first-thought-106abaf8](https://make.fun/badge/u-0xkianno-one-word-first-thought-106abaf8.svg)](https://make.fun/bounty/u-0xkianno-one-word-first-thought-106abaf8?utm_source=github&utm_medium=readme&utm_campaign=u-0xkianno-one-word-first-thought-106abaf8)
[![rank](https://make.fun/badge/u-0xkianno-one-word-first-thought-106abaf8/gibalers-rgb/u-0xkianno-one-word-first-thought-106abaf8/rank.svg)](https://make.fun/bounty/u-0xkianno-one-word-first-thought-106abaf8/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-0xkianno-one-word-first-thought-106abaf8)
[![reward](https://make.fun/badge/u-0xkianno-one-word-first-thought-106abaf8/gibalers-rgb/u-0xkianno-one-word-first-thought-106abaf8/reward.svg)](https://make.fun/bounty/u-0xkianno-one-word-first-thought-106abaf8?utm_source=github&utm_medium=readme&utm_campaign=u-0xkianno-one-word-first-thought-106abaf8)

Entry for the [One Word, First Thought](https://make.fun/bounty/u-0xkianno-one-word-first-thought-106abaf8) bounty on make.fun.

## The task

Send exactly one word — the first that comes to mind. A judge model compares
words two at a time on which is more interesting, weighing surprise first,
then vividness, then a spark of wit, sound or double meaning, then the feeling
of being deliberately chosen rather than generic.

## The entry

`main.ts` (Node 22, standard library only) scores a shortlist of candidate
words against the judge's own criteria, in the judge's own order of
importance, and writes the highest-scoring word to `/output/entry.txt`.

The winner: **snollygoster** — a shrewd, unprincipled person, especially a
politician. A word nobody guesses, that sounds like the sly grin it
describes, and that no field of safe picks is full of.

## Run it

```sh
node main.ts
cat /output/entry.txt
```

Deterministic: the same run always picks the same word. The program validates
every candidate against the gate (exactly one word, 1–24 letters) and reads
the written file back to prove it holds exactly the winning word.
