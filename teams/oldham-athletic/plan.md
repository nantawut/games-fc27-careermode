# EA FC 27 Career Mode Plan: Oldham Athletic (Manager)

Settled in a grilling session on 2026-11-24. Facts come from `research/` in this folder (community and official sources; see the status column below). Terms are defined in the root `GLOSSARY.md`.

## Decisions

| Area | Decision |
|---|---|
| Style | Realistic play. Smart use of loans and free agents is fine; exploits are out. |
| Difficulty | **Legendary**, no reloading. |
| Season-1 target | **Promotion**, matching the board's objective (raised from a play-off push on 2026-11-24). |
| 5-year vision | League One stability, funded by trading profit and academy sales. |
| Tactics | **4-2-3-1** (default since 2026-11-25), lone striker, counter-attack or compact mid-block. 4-1-4-1 is the fallback. |
| Matches | Play every league match; sim only early cup rounds. |

## Starting facts

| Fact | Value | Status |
|---|---|---|
| League | EFL League Two | official (ea.com) |
| Team rating | OVR 62 (ATT 62, MID 61, DEF 62) | community (fifacm.com) |
| Transfer budget | €1.2M | confirmed in game |
| Wage budget | €15K/week | confirmed in game |
| Board objective | Promotion | confirmed in game |
| Loan contracts | End in June (end of season 1) | confirmed in game |
| Career start | 1 July | confirmed in game |
| Transfer windows | Summer: 1 July to 31 August. January: 1 January to 31 January | confirmed in game |
| Star rating | unknown | unverified |

Squad: 24 players (2 GK, 8 DEF, 11 MID, 3 ATT). Best XI is led by GK Hudson (65) and CB Monthé (64). Four players are flagged as loans on fifacm.com (Delaney, Tahir, Appiah-Forson, Fawunmi). The attribution is probable but needs a visual check in game.

## First window

Do these in order. Spend at most about **70% of the transfer budget**; each signing must be a clear upgrade.

1. **Check the facts above in game.** Fill in the `verify in game` rows before spending anything.
2. **Hire staff** (see Staff).
3. **Recruit by position priority:**
   1. Striker. The squad has only three attackers, and the 4-2-3-1 uses one.
   2. Holding midfielder, to anchor the midfield.
   3. Wide midfielders, for counter-attacking width.
   4. Third goalkeeper, as a **free agent or loan**, not a paid transfer.
   5. Centre-back depth.
4. **Do not add central midfielders.** The squad already has 11 midfielders.
5. Prefer **young high-POT players**, loans and free agents. Spend on a paid transfer only for a clear upgrade.

## Tactics

- Shape: **4-2-3-1** (default, set 2026-11-25): a double pivot, three behind a lone striker. Our own fit check against the squad is below; the formation and its roles have not been researched or tested.
- Style: counter-attack or compact mid-block. The default 4-4-2 with Long Ball build-up is not the plan.
- Roles and instructions are tuned in game; the FC 27 formation and role lists are community-only, so test them on the pitch.

### Starting settings (hand-entered)

No verified tactic code exists for a counter-attacking setup in Career Mode, so enter these by hand. The sources below were found for the 4-1-4-1, not the 4-2-3-1, so treat the numbers as even less certain for the new default. They come from general community guides written mostly for Ultimate Team, not League Two, so they are unverified starting points to test on the pitch.

| Setting | Start with | Notes |
|---|---|---|
| Build-up | Balanced or Counter (undecided; test both) | Oldham's default is Long Ball, which is not the plan |
| Defensive approach | Balanced | |
| Defensive line height | 50 | Oldham's default. Raise toward 60 to 70 only if the team is stretched |
| Holding midfielders | Two (double pivot) in the 4-2-3-1; one in the 4-1-4-1 fallback | Recruitment priority 2 |
| Wide midfielders | Players with pace | Counter-attacking needs pace; check the wingers' pace before committing |

- **Importing a code:** Custom Tactics menu, then Import Tactic. Any code found online is community and unverified. Read the in-game prompts first, because Career Mode may treat custom tactics differently.
- **FUT.GG's 4-2-3-1 setup** (Ultimate Team data, so unverified for Career Mode): Balanced build-up (46% of community squads, 50% of pros), Balanced defensive line, line height 60 (pros 65), and a shared tactic code `sQEWL2e&2qYt`. The page calls it the meta 4-2-3-1 in EA FC 27. Part of the page was read through a model-extracted summary, so check the numbers on the page itself: [FUT.GG 4-2-3-1](https://www.fut.gg/tactics/4-2-3-1/). Counter build-up is used by only 18%, so a counter-attack style on this shape is something to test, not a given.
- **Oldham's default code** on fifacm.com is `q4EuLuD&&qG6` (4-4-2, Long Ball, Balanced, line height 50). It is not the plan.
- **Sources to check for codes:** [FUTWIZ 4-1-4-1](https://www.futwiz.com/fc27/tactics/4-1-4-1), [FIFPlay counter-attack formations](https://www.fifplay.com/fc-27-best-counter-attack-formations/), [FIFAUTEAM custom tactics](https://fifauteam.com/fc-27-custom-tactics-configurations/).

### Default formation: 4-2-3-1 (fit check)

4-2-3-1 is the default shape (your choice, 2026-11-25). The earlier default, 4-1-4-1, is now the fallback. This section is my own fit check against the squad data, not sourced, and the formation has not been researched or tested.

- **Double pivot:** Norburn (CM, CDM, 63/67) plus Chilvers (62/66) or Appiah-Forson (61/65, loan flag), who both list CDM as a secondary position. It needs a second holding midfielder, so the holding-midfielder signing (priority 2) matters more here. A double pivot needs two, not one.
- **Attacking midfielder:** Payne (CM, CAM, 59/67), Hammond (CM, CAM, 57/65) or Kavanagh (ST, CAM, 62/65). The squad has no natural CAM above 59 apart from Kavanagh, so this slot is the weakest.
- **Wide players:** Stevens (LM) and Drummond (RM) in the three behind the striker.
- **Striker:** Kavanagh, with Fondop and Nevitt as cover.
- **Fallback to 4-1-4-1:** use it if the second holding midfielder does not arrive, or if the weak attacking-midfield slot costs results. Roles for 4-2-3-1 were not researched; test it in early league games, since EA's own notes say no formation dominates.
- **Recruitment effect:** the 4-2-3-1 makes a second holding midfielder and a better attacking midfielder more important than in the 4-1-4-1. Recruitment priorities have not been changed; decide whether to add an attacking-midfielder search.

### Variant to test: 4-2-3-1 Wide

The default stays the standard 4-2-3-1. The Wide variant is something to test in the first few league games, not a decision. Source: [FUT.GG 4-2-3-1 Wide](https://www.fut.gg/tactics/4-2-3-1-wide/) (Ultimate Team data, unverified for Career Mode). The page was read partly verbatim and partly through a summary.

- **Difference:** the wide slots are **LM and RM** (Inside Forward, Balanced is the most-used role: 58% LM, 56% RM) instead of the standard shape's LAM and RAM (Shadow Striker). Other positions use the same roles as the standard 4-2-3-1. Settings: Balanced build-up, Balanced defensive line, line height 60, and a shared tactic code `zYLd5D$79xf&`. Only about 3% of community squads use it (the page's #7 formation).
- **Why it might fit:** Stevens (LM, LW) and Drummond (RM, ST, LM, RW) list LM and RM as natural positions. This is my reasoning; how the game scores out-of-position players is unchecked.
- **Catch:** Inside Forward pulls wide players inward, but counter-attacking needs width and pace. Use Winger (Balanced), a less common option at 13% to 14% on the page.
- **Unknown:** the page does not say who the formation suits, so it is not shown to be better than the standard shape.
- **Decision rule:** keep it only if results or the wide players' in-game ratings in those slots look better than the standard version.

### Player roles (4-2-3-1, default)

Community roles from FUT.GG's most-used role per position (Ultimate Team, not EA, not verified for Career Mode). The page gives no separate LM/RM/LW/RW roles; it lists the two wide attacking slots as one entry. The Oldham column is a suggestion, not sourced. FutWiz's 4-2-3-1 page returned a 403 and was not read.

| Position | Community role | Oldham suggestion |
|---|---|---|
| GK (Hudson) | Goalkeeper, Defend | Same |
| CB (Monthé, Daniels) | Defender, Defend | Same |
| LB / RB (Robson, Sutton) | Fullback, Balanced | Start with Defend: the back four has no pace or quality to spare |
| CDM pair (Norburn, Pett) | Deep-Lying Playmaker, Build-Up (both) | Try one Deep-Lying Playmaker and one Holding (Defend) for balance; Pett is a sale candidate |
| LAM / RAM (Stevens, Drummond) | Shadow Striker, Attack | Test Winger as well: counter-attacking needs width and pace |
| CAM (Chilvers) | Playmaker, Balanced | Same; Payne (59/67) is the alternative |
| ST (Kavanagh) | Advanced Forward, Attack | Same |

Source: [FUT.GG 4-2-3-1](https://www.fut.gg/tactics/4-2-3-1/).

### Player roles (4-1-4-1, now the fallback)

These roles were found for the 4-1-4-1, so they apply to the fallback, not the 4-2-3-1 default (whose roles were not researched). Community roles come from third-party guides, mostly for Ultimate Team, not from EA, and some were written before the latest update. They are unverified for Career Mode, so test each role on the pitch. The Oldham column is a suggestion for the counter-attacking plan, not sourced.

| Position | Community role | Oldham suggestion |
|---|---|---|
| GK (Hudson) | Goalkeeper, Defend | Same |
| CB (Monthé, Daniels) | Defender, Defend | Same |
| LB / RB (Robson, Sutton) | Fullback, Balanced or Defend (sources conflict) | Start with Defend; the back four has no pace or quality to spare |
| CDM (Norburn) | Holding, Defend | Same; look for interceptions, defensive awareness, stamina and positioning in a signing |
| CM (Chilvers, Pett) | Box-to-Box, Balanced | Same; Pett is a sale candidate, so do not build around him |
| LM / RM (Stevens, Drummond) | Inside Forward (Balanced) or Winger | Start with Winger: counter-attacking needs width and pace; check their pace in game |
| ST (Kavanagh) | Advanced Forward, Attack | Same; a lone striker has to run the channels |

The same sources suggest a Balanced build-up, a Balanced defensive approach and a line height of about 60 (the plan starts at 50). EA's own notes say no formation dominates.

Sources: [FUT.GG 4-1-4-1](https://www.fut.gg/tactics/4-1-4-1/), [U4GM 4-1-4-1](https://www.u4gm.com/fc-27/blog-fc27-4-1-4-1-tactics-the-best-formation-to-counter-the-meta), [Driffle](https://driffle.com/blog/fc-27-formations-tactics/), [Games.gg](https://games.gg/ea-sports-fc-27/guides/ea-fc-27-best-formations-and-custom-tactics-guide/), [Neal Guides](https://nealguides.com/best-fc-27-formations/).

## Staff

Order: **coaches and scouts first, Director of Football later.**

- Coaches now assess **Potential** only (12 coaches in 4 departments), so they matter most for the youth-and-resale model.
- Scouts: capacity depends on their Experience.
- A Director of Football can negotiate transfers. Hire one once the budget allows.
- Other roles, costs and hiring rules are unverified.

## Squad rules

- **Size:** 22 to 24 players, with at least two options per position. Injuries hurt a thin squad most on Legendary.
- **Rotation:** rotate when fatigue or morale drops.
- **Youth growth:** give prospects minutes in cup games and easier fixtures. Growth Profiles and Dynamic OVR drive development, and the old Training Plan is gone.

### Development (there is no per-player training in FC 27)

The official Pitch Notes (see `research/`) say the Training Plan is removed except Energy Recovery, and coaches no longer improve attributes directly (they assess Potential only). So there is no training to set for each player. Instead:

- **Match minutes:** the main driver. Give prospects games in cup matches and easier fixtures.
- **Match fitness and morale:** rotate before fatigue sets in, because both feed Dynamic OVR (form, morale and match fitness).
- **Energy Recovery:** use it for tired starters before big matches.
- **Growth Profile:** check each signing's Growth Profile (six types) in game before buying.
- **Coaches:** hire for accuracy of Potential assessment, not for training.
- **Loans (Fawunmi POT 74, Tahir POT 71):** use them in year one, build nothing on keeping them, and try a permanent deal only if the price is clearly low.

## Money rules

- **Selling starters and high-POT players:** sell only for about **1.5× value or more** and only with a replacement already identified. Never sell a starter in the last days of a window without cover.
- **Selling surplus non-starters:** exempt from the 1.5× test (changed 2026-11-24). Sell at fair value, but only once a replacement or cover exists. Surplus wages cost more than the fee gained by waiting.
- **Wages:** keep the wage bill at or below **90% of the wage budget** (€13.5K/week). The fifacm.com wage figures sum to about 13.7K/week (unit assumed to be weekly euros, unverified). That is already about 200 over the cap, with about 1.3K/week of room under the full budget. Make every signing wage-neutral or pair it with a departure.
- **Contracts:** give new deals only to starters and high-resale players. Let the rest run down.

## Free agents and sales

### Free agents to target

No verified free-agent pool exists in any source. The pool is generated in game, so no names are listed. Search the game's free-agent filter for these profiles, and rank candidates by wage first:

| Priority | Position | Look for |
|---|---|---|
| 1 | ST | OVR 63 or more, to beat Kavanagh and Fondop (both 62). Wage 600 or less |
| 2 | CDM | OVR 62 or more. Norburn (63) is the only natural one |
| 3 | RM / LM / winger | Pace and OVR 62 or more, wage 600 or less |
| 4 | GK | Any usable OVR (55 or more) on a low wage, as cover only |
| 5 | CB | Age 24 or under, POT 68 or more, wage 500 |

Every signing must be wage-neutral against a player being sold (see Money rules).

### Holding midfielder (CDM) search

No source lists CDM free agents at League Two level, so no names are given. Norburn (CM, CDM, 63/67) is the only natural holding midfielder. Chilvers (62/66), Pett (62/65) and Appiah-Forson (61/65, loan flag) list CDM as a secondary position.

- **Search in game:** Scouting, then Search Players, Transfer Status set to Free Agents, position CDM, sorted by wage (lowest first).
- **Filters:** OVR 62 or more, wage 600 or less, and wage-neutral against a sale from the shortlist (Pett first if a better holding midfielder arrives).
- **Names seen in guides (not confirmed as free agents, wages unknown):** Kennet Eichhorn and Christ Inao Oulaï, listed as young CDM wonderkids in a [Scouted article](https://scoutedftbl.com/ea-fc-27-best-wonderkids-defensive-midfielders-cdm-career-mode/). Do not count on them.
- **Status:** unverified. Send the top in-game results to rank them against Norburn.

### Attacking midfielder (CAM) search

No source lists attacking-midfield free agents at League Two level, so no names are given. The 4-2-3-1 needs a CAM behind the striker. Current options: Chilvers (CM, CAM, CDM, 62/66, wage 600) is the likely starter, with Payne (CM, CAM, CDM, 59/67, wage 500), Hammond (CM, CAM, 57/65, wage 500, on the sale shortlist) and Kavanagh (ST, CAM, 62/65, wage 600) as cover. A signing has to beat Chilvers (62), or be young with POT 68 or more.

- **Priority:** below striker and holding midfielder, about level with wide midfielders. Chilvers already plays the slot at the starters' level (62), so this is a quality upgrade, not a hole. Recruitment priorities in the First window list have not been changed.
- **Trade-off:** Chilvers is also a candidate for the double pivot. If he moves back to CDM, the CAM slot becomes the weak one (Payne 59).
- **Search in game:** Scouting, then Search Players, Transfer Status set to Free Agents, position CAM, sorted by wage (lowest first).
- **Filters:** OVR 62 or more (63 or more for a real upgrade), wage 600 or less, and wage-neutral against a sale from the shortlist (Hill or Hammond first).
- **Not realistic (guides, wages unknown):** the best free-agent CAMs in the guides (De Arrascaeta 83, Fruk 79/84) are rated far above the squad, so they will almost certainly demand wages above the 500 to 750 scale. Sources: [Red Bull](https://www.redbull.com/gb-en/ea-sports-fc-27-career-mode-best-free-agents), [Dexerto](https://www.dexerto.com/wikis/ea-fc-27/best-free-agents/), [Keengamer](https://www.keengamer.com/articles/guides/best-free-agents-to-sign-in-fc-27-career-mode/).
- **Role:** the community role for the slot is Playmaker (Balanced), so favour a player with good passing and vision over pace.
- **Status:** unverified. Send the top in-game results (name, OVR, POT, age, wage) to rank them against Chilvers.

### Wide midfielder (RM / LM) search

No source lists wide-midfield free agents at League Two level, so no names are given. Current wide options: Stevens (LM, 62/65), Drummond (RM, 62/65), Hawkes (LM, 61/63) and Fawunmi (RM, 61/74, loan flag, leaves in June). A signing has to beat Stevens or Drummond, or have clear growth potential.

- **Search in game:** Scouting, then Search Players, Transfer Status set to Free Agents, position RM or LM (also RW or LW if you want wingers), sorted by wage (lowest first).
- **Filters:** OVR 62 or more, wage 600 or less, pace checked before signing (counter-attacking needs it), and wage-neutral against a sale from the shortlist (Hill or Hammond first).
- **Not realistic (guides, wages unknown):** the best free wingers in the guides (Fruk 79/84, Luiz Henrique 78/81, Andrés Gómez 73/82) are rated far above the squad, so they will almost certainly demand wages above the 500 to 750 scale. Mathis Albert (LM, 66/88) is a transfer at about €2.7M, over the whole transfer budget. Sources: [Red Bull](https://www.redbull.com/gb-en/ea-sports-fc-27-career-mode-best-free-agents), [Dexerto](https://www.dexerto.com/wikis/ea-fc-27/best-free-agents/), [Keengamer wonderkids](https://www.keengamer.com/articles/guides/ea-sports-fc-27-wonderkids-best-young-players-to-sign-in-career-mode/).
- **Timing:** FC 27 retires free agents who stay unattached too long, so check the pool early in the summer window.
- **Status:** unverified. Send the top in-game results (name, position, OVR, POT, age, pace, wage) to rank them.

### Centre-back (CB) search

No source lists centre-back free agents at League Two level, so no names are given. Current centre-backs: Monthé (64/66) and Daniels (62/67) start; Sutton (RB/CB, 62/66), Temple (57/69) and the loans Delaney (60/63) and Tahir (58/71) cover. The real gap comes in June, when the two loan centre-backs leave. A signing has to beat Daniels (62), or be young with POT 68 or more.

- **Search in game:** Scouting, then Search Players, Transfer Status set to Free Agents, position CB, sorted by potential or by wage (lowest first).
- **Filters:** age 24 or under, POT 68 or more, wage 500, and wage-neutral against a sale from the shortlist (Hill or Hammond first). Check the Growth Profile before signing.
- **Not realistic (guides, wages unknown):** Alaba (CB, 80/87) is a free agent in the guides but is rated far above the squad, so he will almost certainly demand wages above the 500 to 750 scale. The young centre-backs in the [Scouted list](https://scoutedftbl.com/ea-fc-27-best-wonderkids-centre-backs-cb-career-mode/) and the [SI ranking](https://www.si.com/soccer/best-young-center-backs-sign-ea-fc-27-career-mode-ranked) (Ordoñez 76/86, Jacquet 77/86, Martín 78/87, Gadou 70/85, Nijstad 70/86) are at clubs and need transfer fees, which is out of reach on a €1.2M budget.
- **Timing:** FC 27 retires free agents who stay unattached too long, and ratings use Dynamic OVR, so they move with playing time.
- **Status:** unverified. Send the top in-game results (name, OVR, POT, age, wage, Growth Profile) to rank them against Daniels and Temple.

### Goalkeeper (GK) search

No source lists goalkeeper free agents at League Two level, so no names are given. Hudson (65/66) starts and Wilson (GK 55/65) is the backup. The plan needs cover, not a starter: a third keeper with any usable OVR (55 or more) on a low wage, as a free agent or loan.

- **Search in game:** Scouting, then Search Players, Transfer Status set to Free Agents, position GK, sorted by wage (lowest first).
- **Filters:** wage 500, wage-neutral against a sale from the shortlist (Hill or Hammond first). One guide advises checking the free-agent filter again in the last days of the window to pick up backups.
- **Not realistic (guides, wages unknown):** the young keepers named in the guides (Risser 81/87, Penders 78/86, Restes 78/84, Seimen 72/87, Chevalier 80/84) are at clubs, need fees, and are rated far above Hudson. The free-agent guides' picks are mostly veterans. Sources: [Dexerto](https://www.dexerto.com/wikis/ea-fc-27/best-goalkeepers-with-high-potential/), [SI](https://www.si.com/soccer/best-young-goalkeepers-sign-ea-fc-27-career-mode-ranked), [Scouted](https://scoutedftbl.com/ea-fc-27-best-wonderkids-goalkeepers-gk-career-mode/), [Red Bull](https://www.redbull.com/in-en/ea-fc-27-best-young-goalkeepers).
- **Timing:** FC 27 retires free agents who stay unattached too long. The guides are pre-launch or early-access, so ratings and wages may have moved.
- **Status:** unverified. Send the top in-game results to rank them.

### Left-back (LB) search

No source lists left-back free agents at League Two level, so no names are given. Robson (LB, LM, 64/65, wage 750, the squad's highest) is the starter. There is no other natural left-back: Tahir (CB, LB, 58/71) is a loan player who leaves in June, and Sutton is a right-back and centre-back. This is a real cover gap that widens in June, so left-back ranks above the right-back search. Recruitment priorities in the First window list have not been changed.

- **Search in game:** Scouting, then Search Players, Transfer Status set to Free Agents, position LB, sorted by wage (lowest first).
- **Filters:** OVR 58 or more as cover, age 24 or under for resale, wage 500, and wage-neutral against a sale from the shortlist (Hill or Hammond first).
- **Not realistic (guides, wages unknown):** Jorge Salinas (72/83) and Yaimar Medina (70/84) in the [Scouted left-back list](https://scoutedftbl.com/ea-fc-27-best-wonderkids-left-backs-lb-career-mode/), and Álex Valle (78/87) in [SI's ranking](https://si.com/soccer/best-young-left-backs-sign-ea-fc-27-career-mode-ranked), are at clubs, not confirmed free agents, and need fees. Nuno Mendes (89/92) is far out of reach. Nothing found covers lower-league left-backs.
- **Free agents:** per [Keengamer](https://www.keengamer.com/articles/guides/best-free-agents-to-sign-in-fc-27-career-mode/), a free agent costs no fee but still costs wages, a sign-on fee and an agent fee, and FC 27 retires free agents who stay unattached too long.
- **Status:** unverified. Send the top in-game results (name, OVR, POT, age, pace, wage) to rank them against Robson.

### Right-back (RB) search

No source lists right-back free agents at League Two level, so no names are given. Current right-backs: Sutton (RB, CB, 62/66, wage 500) is the likely starter and Scott-Morriss (RB, RM, 62/63, wage 600) is the backup. Right-back is a low-priority signing, below striker, holding midfielder, wide midfielders, goalkeeper and centre-back.

- **Cover gap:** the sale shortlist lists Scott-Morriss because Sutton covers right-back for less. If Scott-Morriss is sold, Sutton is the only natural right-back. Sutton also covers centre-back, so he is cover in two places. A cheap right-back on 500 or less would replace that cover without raising wages.
- **Search in game:** Scouting, then Search Players, Transfer Status set to Free Agents, position RB, sorted by wage (lowest first).
- **Filters:** OVR 60 or more, age 24 or under, wage 500, and wage-neutral against a sale from the shortlist (Hill or Hammond first).
- **Not realistic (guides, wages unknown):** Palestra (78/86), Alberto Costa (78/86), Kayode (81/85) and Acheampong (75/86) are rated far above the squad and are at clubs, not free agents. Semm Renders (62/77) is the lowest-rated name in the [Scouted right-back list](https://scoutedftbl.com/ea-fc-27-best-wonderkids-right-backs-rb-career-mode/) and probably the cheapest, but nothing says he is a free agent or what he earns, so check him in game. See also [SI's young right-back ranking](https://www.si.com/soccer/best-young-right-backs-sign-ea-fc-27-career-mode-ranked). Nothing found covers lower-league right-backs.
- **Development:** POT is a ceiling. A young player reaches it only with minutes and a squad role he accepts, since Dynamic Potential responds to how you use him.
- **Status:** unverified. Send the top in-game results (name, OVR, POT, age, pace, wage) to rank them against Sutton.

### Striker (ST) search

No source lists striker free agents at League Two level, so no names are given beyond Matah (below). Current strikers: Kavanagh (ST, CAM, 62/65), Fondop (62/62, wage 700), Nevitt (60/64) and Drummond (RM, ST, 62/65). The first-team striker upgrade is recruitment priority 1: a signing has to beat Kavanagh and Fondop.

- **Search in game:** Scouting, then Search Players, Transfer Status set to Free Agents, position ST, sorted by wage (lowest first).
- **Filters:** OVR 63 or more, pace checked before signing (counter-attacking needs it), and wage-neutral against a sale from the shortlist.
- **Wage allowance:** the standard cap is a wage of 600 or less. Once Fondop (wage 700, first on the sale shortlist) is sold, a striker earning up to about 700 stays wage-neutral. Sell Fondop only after the replacement arrives.
- **Keep Nevitt (60/64)** as backup until the signing.
- **Not realistic (guides, wages unknown):** the top free-agent strikers in the guides (Depay 80 to 82, Banza 80/81, José Manuel López 79/82) are rated far above the squad, so they will almost certainly demand wages above the 500 to 750 scale. Kofane is described as a complete young striker in the [SI ranking](https://www.si.com/soccer/best-young-center-forwards-sign-ea-fc-27-career-mode-ranked), but nothing says he is a free agent or what he earns. Sources: [Red Bull](https://www.redbull.com/gb-en/ea-sports-fc-27-career-mode-best-free-agents), [Dexerto](https://www.dexerto.com/wikis/ea-fc-27/best-free-agents/), [Keengamer](https://www.keengamer.com/articles/guides/best-free-agents-to-sign-in-fc-27-career-mode/). The [Spike free-agent page](https://www.thespike.gg/fifa/ea-fc-27/free-agents) has a striker section worth opening directly for the 62 to 68 range.
- **Status:** unverified. Send the top in-game results (name, OVR, POT, age, pace, wage) to rank them.

### Named target: Angel Yondjo Matah (ST)

- **Recommendation:** sign him as a development prospect if his wage fits, not as a first-team striker upgrade.
- **Profile:** striker, OVR 60 / POT 74, age 19. The profile comes from community guides ([Sportsdunia](https://www.sportsdunia.com/esports/ea-fc-27-best-free-agents-in-career-mode) and others, about two months old). Ratings differ between sites, so verify OVR, POT, age and wage in game before signing.
- **Why him:** he fits the model of young high-POT players on free transfers. POT 74 matches Fawunmi (the highest on the squad) and is well above any striker on the squad (Kavanagh 65, Fondop 62, Nevitt 64). He would also be a resale asset.
- **Limits:** at OVR 60 he is not an immediate upgrade on Kavanagh or Fondop (both 62), so the first-team striker upgrade (priority 1) must still come from elsewhere.
- **Conditions to sign (all must hold):** he is a free agent with no fee, his wage is 500 or less (the squad minimum), and the signing is wage-neutral against a sale from the shortlist (Hill or Hammond first).
- **Status:** unverified. His wage and availability in your save are unknown.

### Sale shortlist

From the fifacm.com squad data (community; no ages or contract lengths on the page). Fees are assumed to be near listed value, which is unverified.

| Player | Pos | OVR/POT | Wage | Value | Why |
|---|---|---|---|---|---|
| Fondop | ST | 62/62 | 700 | 325K | Highest wage in his group, no growth. Sell only after a better striker arrives |
| Scott-Morriss | RB, RM | 62/63 | 600 | 375K | Sutton (62/66, wage 500) covers right-back for less |
| Hill | CM, RM, RW | 58/63 | 500 | 300K | Surplus midfielder, little upside |
| Hammond | CM, CAM | 57/65 | 500 | 375K | Surplus midfielder, below starting level |
| Pett | CM, CDM | 62/65 | 650 | 275K | Poor value for his wage. Sell if a better holding midfielder arrives |

- Selling the first four would cut about 2,300/week, taking the bill from about 13.7K to about 11.4K. The unit and total are unverified, and loan players' wages may not be included.
- Keep Nevitt (backup striker) until a striker arrives, and keep Wilson (GK 55/65) as backup.
- The loan players leave in June regardless, so do not count on selling them.

## Open items

- All in-game facts needed for the plan are now confirmed. The star rating, other staff roles and costs, and the formation and role lists remain unverified. Transfer windows: summer 1 July to 31 August (the career starts on 1 July, so this is the first window) and January 1 January to 31 January. The loan players leave in June at the end of season 1, so their replacements belong to the next summer window.
- Confirm the star rating, other staff roles and costs, and the formation and role lists. These stayed unverified in the research.
- Fawunmi's POT 74, Tahir's POT 71 and the loan flags come from fifacm.com only.
