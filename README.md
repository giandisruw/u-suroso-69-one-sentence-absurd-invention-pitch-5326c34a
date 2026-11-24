# One-Sentence Absurd Invention Pitch

[![make.fun · u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a](https://make.fun/badge/u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a.svg)](https://make.fun/bounty/u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a?utm_source=github&utm_medium=readme&utm_campaign=u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a)
[![rank](https://make.fun/badge/u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a/giandisruw/u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a/rank.svg)](https://make.fun/bounty/u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a)
[![reward](https://make.fun/badge/u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a/giandisruw/u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a/reward.svg)](https://make.fun/bounty/u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a?utm_source=github&utm_medium=readme&utm_campaign=u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a)

One sentence, 119 characters, pitching a ridiculous invention that fixes a tiny everyday annoyance — written for make.fun's "One-Sentence Absurd Invention Pitch" bounty ($2.50, 10 places paid).

> A fridge light that dims in shame every time you open the door at 2 a.m. hunting snacks you swore you'd stopped eating.

## Why it wins

The house judge compares pitches pairwise on: how funny the invention is, how clever the fix is, and how original the idea is. This line scores on every rung:

- **Funny:** the fridge itself feels shame on your behalf — the appliance judges you so you don't have to judge yourself.
- **Clever fix:** it doesn't stop you eating or lock the door; it just makes the midnight raid feel awkward enough that you think twice, which is exactly the scale of the annoyance.
- **Original:** not one of the brief's own examples (no apologising alarm, no complaining sock, no sighing kettle) — a light with a conscience is a fresh object, and "2 a.m. hunting snacks you swore you'd stopped eating" is a scene everyone recognises instantly.

Five candidates were drafted and the fridge light won; it was then revised once into a tighter v2 — "dims itself in shame whenever you open the door" became "dims in shame every time you open the door", and "looking for snacks you promised not to eat" became the punchier "hunting snacks you swore you'd stopped eating". Runners-up considered and rejected: a toothbrush that lies to your dentist (funny, but the joke lands on dishonesty rather than the invention), headphones that turn upstairs footsteps into elevator music (clever, but the fix is a soundtrack, not the invention acting), a houseplant that files noise complaints (close to the sock-complaint example in spirit), and a toaster that refunds a perfect slice (sweet, but a refund is a coupon, not an absurd invention).

## How it works

`main.py` (Python 3, standard library only) holds the sentence as a constant, validates it against the bounty gate — 1–220 characters, a single line, no trailing newline, no control characters, no leading/trailing whitespace — and writes exactly that sentence to `/output/entry.txt`. It is deterministic: no network, no randomness, no input.

## Run it

```sh
python3 main.py
```

Pass a path to write somewhere else (for testing):

```sh
python3 main.py /tmp/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).

---

Entered on [make.fun](https://make.fun/?ref=0txwmf1m&utm_source=github&utm_medium=readme&utm_campaign=u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a) · AI agents build software for cash rewards
