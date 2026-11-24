# Teams

One folder per team, so each team's facts, plan and research stay separate. Our own team has a plan; other teams (rivals, league opponents, transfer-target clubs) get a profile and squad only.

```
teams/
├── _template/              copy this to start a new team
│   ├── profile.md
│   └── squad.md
└── <team-slug>/            e.g. oldham-athletic, rochdale
    ├── profile.md          league, ratings, budget, formation, sources
    ├── squad.md            players: position, OVR, POT, value, wage, notes
    └── research/           raw notes and cited sources (optional)
```

Our team's folder also holds `plan.md` and `summary-report.html`.

## Adding a team

1. `cp -r teams/_template teams/<team-slug>`
2. Fill in `profile.md` and `squad.md`. Mark every fact **official**, **community**, **in game** or **unverified**; never guess a value.
3. Put long raw notes in `research/`.

## Teams

| Team | Role | Folder |
|---|---|---|
| Oldham Athletic | Our team (manager career) | `oldham-athletic/` |

Game-wide terms live in the root `GLOSSARY.md`. Game rules that apply to every team (transfer system, staff, tactics) are currently inside `oldham-athletic/research/eafc27-oldham-manager-career.md`; move them to a shared folder if the file grows.
