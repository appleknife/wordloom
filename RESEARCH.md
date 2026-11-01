# Keeping it fun without making it useless

Research notes for Wordloom, October 2026. What the evidence actually says about
gamified learning, motivation, streaks, and vocabulary retention — and what it
means for this app specifically.

The short version: **gamification is seasoning, not food.** It reliably improves
engagement a little, and it can actively hurt when the rewards become the point.
Retention comes from retrieval, spacing and difficulty. Fun comes from autonomy,
competence and — much more than most apps admit — other people.

---

## 1. Gamification works, but the effect is small and conditional

The best-known meta-analysis (Sailer & Homner, 2020, 19–22 studies) found small
positive effects: cognitive learning **g = .49**, motivational **g = .36**,
behavioural **g = .25**.

Two moderator findings matter here:

- **Game fiction didn't help** learning or motivation. Story dressing is not the
  active ingredient.
- **Competition combined with collaboration** beat competition alone, especially
  for behaviour. Social interaction was the one moderator that reliably moved
  behavioural outcomes.

A 2024 meta-analysis of 35 interventions (2,500 participants) is more sobering:
gamification raised intrinsic motivation by only **g = .26**. But it moved the
underlying needs unevenly:

| Need | Effect |
| --- | --- |
| Relatedness | **g = 1.78** (large) |
| Autonomy | **g = .64** (moderate) |
| Competence | **g = .28** (small) |

That table is the single most useful thing in this document. The lever with the
biggest effect by far is *other people*, and Wordloom currently has none.

Also: effects were largest for interventions lasting **1–3 months** (g = .61) and
roughly zero beyond a semester. Short arcs beat indefinite grinds.

> Sailer & Homner (2020), *Educational Psychology Review* —
> https://link.springer.com/article/10.1007/s10648-019-09498-w
> Huang et al. (2024), *ETR&D* — https://link.springer.com/article/10.1007/s11423-023-10337-7

## 2. Rewards can quietly ruin the thing they reward

The classic meta-analysis of 128 experiments (Deci, Koestner & Ryan, 1999) found
that *expected tangible rewards* undermine free-choice intrinsic motivation:
**d = −.40** for engagement-contingent, **−.36** completion-contingent, **−.28**
performance-contingent.

But **positive feedback increased** both free-choice persistence (d = +.33) and
self-reported interest (d = +.31).

That distinction is the whole design brief:

- "You get 50 coins for opening the app" → this is a controller. It erodes.
- "You recalled seven of eight, including two words from three weeks ago" →
  this is information about competence. It builds.

A 2026 review documents the failure mode in the wild: users optimizing the game
instead of the learning, up to one Duolingo user saying they were *"literally
seeing real learning as an obstacle to my success in gamification."* That is
motivational drift, and it is the reason to avoid points economies.

> Deci, Koestner & Ryan (1999), *Psychological Bulletin* —
> https://pubmed.ncbi.nlm.nih.gov/10589297
> Woolley (2026), *Consumer Psychology Review* —
> https://myscp.onlinelibrary.wiley.com/doi/10.1002/arcp.70004

## 3. Streaks are powerful and slightly dangerous

Seven experiments with 4,000+ people (Silverman & Barasch, 2023): participants
were more likely to repeat a behaviour when an **intact** streak was highlighted
than an equally long **broken** one — 66.2% vs 57.9% — even though the actual
behaviour was identical.

Three practical findings:

1. **Broken streaks demotivate** more than the missed day itself. Don't advertise
   the break.
2. **Easy repair weakens the streak.** If a streak can always be restored, it
   stops meaning anything.
3. **Emergency reserves work.** A 7-day goal with **two allowed skip days** beat
   both a 5-day goal and a strict 7-day goal. The reserve removes the "I've
   already failed" cliff without removing the goal.

Commitment was also higher when the streak was framed as a **daily, short-term,
private** goal rather than an indefinite public one.

> Silverman & Barasch (2023), *Journal of Consumer Research* — summary:
> https://knowledge.insead.edu/marketing/consumer-streaks-are-motivating-key-keeping-them-alive
> Emergency reserves: Sharif & Shu, discussed in Woolley (2026) above.

## 4. Habit takes about two months, and one missed day doesn't matter

Lally et al. (2010) followed 96 people for 12 weeks: median time to 95% of
automaticity was **66 days**, with an enormous range of **18 to 254 days**.
Missing a single opportunity "did not materially affect the habit formation
process." Erratic repetition did.

Two implications: design the first **60–90 days** as the real product, and stop
treating a missed day as a failure — it measurably isn't one.

> Lally et al. (2010), *EJSP* — https://onlinelibrary.wiley.com/doi/full/10.1002/ejsp.674
> Plain-language summary: https://www.ucl.ac.uk/news/2009/aug/how-long-does-it-take-form-habit

## 5. Retention comes from retrieval, spacing, and being wrong first

The learning science here is unusually consistent:

- **Retrieval practice beats rereading.** Testing yourself produces better
  long-term retention than extra study, across vocabulary and general material.
- **Spacing beats massing**, and *expanding* gaps are at least as good as fixed
  ones.
- **Desirable difficulties**: conditions that make learning feel harder and
  slower often produce better retention. Feeling fluent is not the same as
  learning.
- **Pretesting works**: guessing before you're taught improves memory for the
  guessed item — meta-analytic **g = .54** — but only for the specific item that
  was guessed (g ≈ .04 for everything else). So guessing is a scalpel, not a
  fog.

Wordloom already does all four: reveal-after-guess, expanding intervals
(1/2/4/8/16/32/64 days), and multiple-choice retrieval. The gap is that every
question is *recognition*. Recognition is the easiest form of retrieval and the
least like using a word in life.

> St Hilaire, Chan & Ahn (2024), *Psychonomic Bulletin & Review* —
> https://pubmed.ncbi.nlm.nih.gov/37640836
> Karatas et al. (2025) on spacing + retrieval in L2 vocabulary —
> https://journals.sagepub.com/doi/full/10.1177/13621688211053525

## 6. Flow: difficulty has to track skill

In a study of 934 students playing an educational game, challenge and skill
together accounted for **47.8% of the variance in engagement**, and challenge had
a direct positive effect on learning — not just via engagement.

Too easy reads as boring; too hard reads as threat. The sweet spot is "just
outside the comfortable" — which is exactly what the useful/stretch lane split and
the 3:1 / 2:1 / 1:1 mix control are for. It just needs to adapt per person rather
than sit at one global setting.

> Hamari et al. (2016), *Computers in Human Behavior* —
> https://www.sciencedirect.com/science/article/pii/S074756321530056X

---

## What this means for Wordloom

| Finding | Where we stand | What to change |
| --- | --- | --- |
| Relatedness is the biggest motivational lever | Solo app, zero social | Add a person: a weekly duel with you, a shared recap |
| Tangible rewards undermine; feedback builds | No coins or points — good | Make praise specific and about recall, never generic |
| Broken streaks demotivate | Streak resets silently | Add two skip days per week; never show the break in red |
| Short arcs beat indefinite grinds | Open-ended | Add 30-word "chapters" with a finish line |
| Habit ≈ 66 days, one miss is fine | Already forgiving | Say so out loud in the copy; set a reminder cue at onboarding |
| Retrieval > recognition | All multiple choice | Add cloze (fill the blank) and free-recall items |
| Pretesting is specific and strong | "Guess first" reveal | Make the guess explicit rather than passive |
| Challenge must track skill | Global mix setting | Let him rate a word too easy / too hard and adapt |
| Autonomy supports motivation | Mix + text size + theme | Let him choose themes, retire words, add his own |

### If we only did three things

1. **Give him someone to play with.** A five-question weekly duel against you, and
   a recap card he can send. This is the largest effect in the literature and the
   only thing the app is completely missing. It also solves the retention problem
   that no amount of design can: someone expecting his score on Sunday.
2. **Replace the raw streak with a "kept" record.** Two skips a week, a 30-word
   chapter with an ending, and a line that reads *"16 of 18 days"* rather than a
   number that can collapse to zero.
3. **Make review produce words, not recognise them.** Cloze sentences first, then
   free recall, then the multiple choice we already have. Keep the multiple choice
   for the first encounter with a word, when recognition is the honest task.

### And what not to add

- No coins, gems, or currency.
- No leaderboard against strangers.
- No "you lost your streak!" notification.
- No badges for opening the app. Badges for *recalling* something old are fine,
  because that is competence information rather than a bribe.

---

## What shipped (October 2026)

Everything above is now in the app. Each decision traces back to a section:

| Shipped | Why | Section |
| --- | --- | --- |
| **Play** tab: pass-and-play duel + link challenge | Relatedness was the largest effect size in the literature (g = 1.78) and the app had none. Competition *with* collaboration beat competition alone. | 1 |
| Head-to-head tally, no points, no timers | Tangible rewards undermine; the score is information, not a currency. | 2 |
| Two rest days a week, amber not red | Emergency reserves beat both a strict and a looser goal; broken streaks demotivate more than the miss itself. | 3 |
| 30-word chapters with an ending | Short-term framing beat indefinite goals for streak commitment. | 3 |
| Retrieval ladder: recognise → cloze → type | Retrieval beats recognition for retention; production is the form that transfers to real use. | 5 |
| "Guess first" reveal, and pretesting in review | Pretesting effect g = .54 for the guessed item. | 5 |
| Specific praise in the summary ("three were old friends") | Positive feedback raises intrinsic motivation; generic praise and badges do not. | 2 |
| Onboarding: name, rival, cue, mix | Cue = implementation intention; mix + name = autonomy (g = .64). | 1, 6 |
| Per-word "too easy / too hard" | Challenge has to track skill; challenge drove both engagement and learning. | 6 |
| No coins, no leaderboards, no guilt notifications | Motivational drift is the documented failure mode. | 2, 3 |

Still open: more words (the bank is 143; chapter 5 runs out), and a shared season
scoreboard once the two phones are actually talking.

## Caveats

Most of this literature is classroom studies with students, often short and
quasi-experimental, and effect sizes in gamification research shrink under
higher methodological rigor. Almost none of it is a 40-year-old man using a
phone app for six months. Treat the numbers as direction, not prophecy — and
treat the first two weeks of real use as the most valuable data we'll get.
