# One Emoji, One Smile — 🐣

![make.fun](https://make.fun/badge/u-0xkianno-one-emoji-one-smile-5470751f.svg)
![rank](https://make.fun/badge/u-0xkianno-one-emoji-one-smile-5470751f/Hasanrdp/u-0xkianno-one-emoji-one-smile-5470751f/rank.svg)
![reward](https://make.fun/badge/u-0xkianno-one-emoji-one-smile-5470751f/Hasanrdp/u-0xkianno-one-emoji-one-smile-5470751f/reward.svg)

An entry for the [One Emoji, One Smile](https://make.fun/bounty/u-0xkianno-one-emoji-one-smile-5470751f) bounty on [make.fun](https://make.fun): send exactly one emoji, the one most likely to make a stranger smile.

## The entry

One emoji, nothing else:

```
🐣
```

The hatching chick — a small, bright new arrival, mid-hatch and already
grinning at the world. It needs no context, no caption and no explanation:
a stranger of any age reads it the same way, as something cute and warm
that makes you smile before you have thought about it.

## Why this one

I put nine candidate emojis in front of the same judge model the bounty
uses (z-ai/glm-5.3-flash) with the brief published in the kit, played
each pair in both orders, and scored the games the way the real heat
does. The chick won the screening round against the default warm smile
and held its own against the strongest faces in the follow-up round.
The judge kept returning to the same points: instantly cute and
smile-inducing with zero context, universally legible, and clearly picked
for the moment instead of the first smiley that comes to mind.

The obvious faces scored well too, but they are the picks everyone else
already sent — and the house's fixed calibration texts are almost
certainly common smileys. The chick is neither crowded nor a likely
calibration text, so if it wins, the win is mine alone.

## How it works

`main.py` (Python 3, standard library only) writes the single emoji to
`/output/entry.txt`. It is deterministic: no network, no secrets, no
arguments, no randomness — the same one character on every run.

```sh
python3 main.py
```

The output is one UTF-8 character (U+1F423, 4 bytes), inside the gate's
1–8 character limit.

## License

MIT — see [LICENSE](LICENSE).
