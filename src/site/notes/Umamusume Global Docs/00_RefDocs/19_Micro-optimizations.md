---
{"dg-publish":true,"dg-path":"00_RefDocs/19_Micro-optimizations.md","permalink":"/00-ref-docs/19-micro-optimizations/","created":"2025-07-27T12:54:13.435+07:00","updated":"2025-07-27T12:58:52.586+07:00"}
---

# Micro-optimizations

## Racing Energy

After winning a race, you have a choice between taking a consistent amount of energy, or gambling on less or more. They average out to the same thing in the long run. There are some situations where it’s optimal to pick one over the other, though. This is most relevant in the third scenario, MANT, where doing 30+ races in a run is normal.

If you race on zero energy, you can be punished. Thus, if one option has the chance to set you to 0 energy, or the chance to keep you above 0 energy, you should choose accordingly. In MANT, on a win, the top option is -20 energy, and the bottom option is either -10 or -25. If you currently have 11~20 energy, then choosing the bottom option is clearly best, as you have a chance to stay above 0. If you have 21~25, then choosing top is best, since getting the -25 energy outcome would put you to 0.

It gets a bit more complicated when you have multiple races in a row. If you’re planning to race three times, and you’re at 41~45 energy, then picking top on the first two races will guarantee you have energy remaining for the third race. If you pick bottom and get -25, then you’re now at 16~20 energy and have to gamble on bottom again and get -10 in order to avoid hitting 0 energy. On the other hand, if you’re at 46+, you can still be at 21+ after a -25, then you can choose the top to remain above 0. Choosing the bottom is best here, since getting -10 twice in a row will help a lot.

Note that you can’t get punished for races that happen on the final turn before an objective, or races that are objectives. In MANT, this means the races at the end of the year. Even if you do Arima Kinen as your third race and have 0 energy, you won’t receive any downside. The same applies in other scenarios, for example in Aoharu Oguri Cap won’t get punished after Takarazuka Kinen in Senior Year, since it’s her objective turn.

## Hint Pruning

You can’t get hints for skills you already own. This applies both to actual hints from cards, and later scenario mechanics like Aoharu Explosions or MANT Rivals. Thus, you can buy skills early to take them out of the hint pool, to increase the chance of getting the other skills. The downside of doing this is that they won’t get discounted by [Fast Learner](https://docs.google.com/document/d/11X2P7pLuh-k9E7PhRiD20nDX22rNWtCpC1S4IMx_8pQ/edit?tab=t.0#heading=h.6yoj151p4ujr) if you obtain it later in the run.

Note that you also can’t get hints for skills that are already at hint level 5, so if that happens, there’s no rush to buy them.

This is mainly used for Debuffer umas. Cards like Rudolf have many hints. Buying them as you get them will increase the chance of getting other debuff hints in the future. However, it can also be used for other umas. In MANT, you can buy things like Pace Chaser Straightaways to make it more likely to get Pace Chaser Corners, for instance. Naturally, for racing umas, you’ll only want to buy skills you actually want, unlike Debuffers who will buy anything the cards give them.

You should also keep in mind what mechanics the scenarios use to give you hints. For example, in Aoharu, the explosions give you hints for aptitudes you have at A, so it’s optimal to have as few A rank aptitudes as possible, making umas like Manhattan Cafe better.

## SSR Chain Events

Whether you finish or even see the chain events for an SSR is mostly random, but it’s also related to how many total chain events are in your deck. Each one competes to be chosen.

In a deck with 6 SSRs, each SSR will finish their chain less often than if it was a deck with 3 SSRs and 3 SRs, for example. If you just wanted to finish one chain (for gallery completion, or for a mission, etc) you could take 1 SSR and 5 Rs to make it highly likely.

As a side note, this is why speedruns use 6 R cards. There are no chain events to take up time.

Cards that can end their chain early are also good for this, such as [Mayano Top Gun](https://gametora.com/umamusume/supports/30072-mayano-top-gun) or [Curren Chan](https://gametora.com/umamusume/supports/30068-curren-chan). Ending the chain removes the later two events from the pool, raising the chance you’ll see the others. Cards with dates, either Friend or Group cards, also don’t have chain events, but their event where they ask to date you counts as one.

## Extra Training

Extra Training is the event that comes up after doing a training, where you can choose to get +5 energy or +5 of the stat you trained and -5 energy. For the most part, you should always choose the energy, unless you’re in a situation where you don’t need energy. For example, a Wit build can usually afford the -5 energy, since their trainings restore energy. Or, if you’re about to rest, or are the day before an energy-restoring event that would put you to full (e.g. the [New Years](https://docs.google.com/document/d/11X2P7pLuh-k9E7PhRiD20nDX22rNWtCpC1S4IMx_8pQ/edit?tab=t.0#heading=h.u0zejp7fpsgz) event).

However, the bond you gain from doing the extra training can be helpful in some situations. For example, you need the chairman’s bond to be at green in order to get your unique skill level up in Senior Year. You’ll also get more stats at the end if she’s fully bonded. If you know you’re low on bond with her, you can do the extra training.

It’s also worth noting here that, according to the patch notes, doing extra training has a chance to cure the Slow Metabolism condition. I haven’t personally seen it happen but also haven’t been in a position to test it.

## Career Race Style

The general early game recommendation is to do Front Runner for every race, regardless of your uma’s aptitude. This avoids the chance of getting surrounded/blocked, which leads to losses in races you should otherwise easily win. It can still happen if you get a late start, but certainly much less. It’s technically the weakest style, but when you outstat the enemies, it doesn’t really matter.

Another consideration though is Stamina. Late Surger uses the least stamina of all the styles, so if it’s a longer race than your uma is trained for, picking Late Surger can help you win. This is especially useful on umas like McQueen, King Halo, and so on.

Later scenarios give you hints for the style you ran with so you’ll generally just do the style hinted at in every one of those races.

> [!info] Navigation
<p><span><a data-tooltip-position="top" aria-label="Umamusume Global Docs/00_RefDocs/00_News" data-href="Umamusume Global Docs/00_RefDocs/00_News" href="Umamusume Global Docs/00_RefDocs/00_News" class="internal-link" target="_blank" rel="noopener nofollow">Index</a><br>
<a data-tooltip-position="top" aria-label="Umamusume Global Docs/00_RefDocs/18_Advanced Training Strategy (URA).md" data-href="Umamusume Global Docs/00_RefDocs/18_Advanced Training Strategy (URA).md" href="Umamusume Global Docs/00_RefDocs/18_Advanced Training Strategy (URA).md" class="internal-link" target="_blank" rel="noopener nofollow">&lt;&lt; Previous</a> | <a data-tooltip-position="top" aria-label="Umamusume Global Docs/00_RefDocs/92_Uma Distances or Styles.md" data-href="Umamusume Global Docs/00_RefDocs/92_Uma Distances or Styles.md" href="Umamusume Global Docs/00_RefDocs/92_Uma Distances or Styles.md" class="internal-link" target="_blank" rel="noopener nofollow">Next &gt;&gt;</a></span></p>
