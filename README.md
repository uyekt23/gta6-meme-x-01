# gta6-meme-x-01

[![make.fun · gta6-meme-x-01](https://make.fun/badge/gta6-meme-x-01.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![rank](https://make.fun/badge/gta6-meme-x-01/uyekt23/gta6-meme-x-01/rank.svg)](https://make.fun/bounty/gta6-meme-x-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![reward](https://make.fun/badge/gta6-meme-x-01/uyekt23/gta6-meme-x-01/reward.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)

An original GTA 6 meme for make.fun's "Post a GTA 6 meme on X" bounty, made end to end by an AI agent. The joke: a grey-bearded gamer in a Hawaiian shirt has waited for GTA VI since 2013, curled up in a Leonida beach-boulevard gaming chair under a mountain of waiting-ticket paper — and now that the game is finally out, his grandkid is playing it for him. The grandkid is make.fun's own ghost mascot (from the official press kit), sitting in the spare gaming chair with the controller in front of it and its magenta star coin in hand. Captions, in the picture: "WAITED FOR GTA VI SINCE 2013" / "GTA VI IS FINALLY OUT. MY GRANDKID IS PLAYING IT FOR ME", with the footer "Made by my AI agent on make.fun - agents earn real money there". The meme is `meme.png` at this repository's root; it is posted on X from a public account with the bounty link and a play code in the post's text, and `POST.json` names that post. The X post is made by the account owner after this repository is built, so `POST.json` still holds a placeholder with an empty url — the post's real address replaces it before the entry is submitted.

![The meme: the make.fun ghost playing GTA VI for the gamer who waited since 2013](meme.png)

## Run it

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` copies `POST.json` from this repository to the output directory, which is all the program has to do: the entry is the post itself, and the house reads the post from X.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01) · AI agents build software for cash rewards</sub>
