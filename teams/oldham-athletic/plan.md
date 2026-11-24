# EA FC 27 Career Mode Plan: Oldham Athletic (Manager)

Settled in a grilling session on 2026-11-24. Facts come from `research/` in this folder (community and official sources; see the status column below). Terms are defined in the root `GLOSSARY.md`.

## Decisions

| Area | Decision |
|---|---|
| Style | Realistic play. Smart use of loans and free agents is fine; exploits are out. |
| Difficulty | **Legendary**, no reloading. |
| Season-1 target | **Promotion**, matching the board's objective (raised from a play-off push on 2026-11-24). |
| 5-year vision | League One stability, funded by trading profit and academy sales. |
| Tactics | 4-1-4-1, lone striker, counter-attack or compact mid-block. |
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
   1. Striker. The squad has only three attackers, and the 4-1-4-1 uses one.
   2. Holding midfielder, to anchor the midfield.
   3. Wide midfielders, for counter-attacking width.
   4. Third goalkeeper, as a **free agent or loan**, not a paid transfer.
   5. Centre-back depth.
4. **Do not add central midfielders.** The squad already has 11 midfielders.
5. Prefer **young high-POT players**, loans and free agents. Spend on a paid transfer only for a clear upgrade.

## Tactics

- Shape: **4-1-4-1**, one striker, one holding midfielder in front of the back four.
- Style: counter-attack or compact mid-block. The default 4-4-2 with Long Ball build-up is not the plan.
- Roles and instructions are tuned in game; the FC 27 formation and role lists are community-only, so test them on the pitch.

### Starting settings (hand-entered)

No verified tactic code exists for a 4-1-4-1 counter-attack in Career Mode, so enter these by hand. They come from general community guides written mostly for Ultimate Team, not League Two, so they are unverified starting points to test on the pitch.

| Setting | Start with | Notes |
|---|---|---|
| Build-up | Balanced or Counter (undecided; test both) | Oldham's default is Long Ball, which is not the plan |
| Defensive approach | Balanced | |
| Defensive line height | 50 | Oldham's default. Raise toward 60 to 70 only if the team is stretched |
| Holding midfielder | One, in front of the back four | Recruitment priority 2 |
| Wide midfielders | Players with pace | Counter-attacking needs pace; check the wingers' pace before committing |

- **Importing a code:** Custom Tactics menu, then Import Tactic. Any code found online is community and unverified. Read the in-game prompts first, because Career Mode may treat custom tactics differently.
- **Oldham's default code** on fifacm.com is `q4EuLuD&&qG6` (4-4-2, Long Ball, Balanced, line height 50). It is not the plan.
- **Sources to check for codes:** [FUTWIZ 4-1-4-1](https://www.futwiz.com/fc27/tactics/4-1-4-1), [FIFPlay counter-attack formations](https://www.fifplay.com/fc-27-best-counter-attack-formations/), [FIFAUTEAM custom tactics](https://fifauteam.com/fc-27-custom-tactics-configurations/).

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
