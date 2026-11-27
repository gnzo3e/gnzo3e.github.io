# gnzo3e.github.io

## Xeneon Edge widgets

Widgets for the Corsair Xeneon Edge, made for iCUE's iFrame widget. Paste the URL into an iFrame widget in iCUE.
<img width="2515" height="703" alt="XeneonEdge-Screenshot" src="https://github.com/user-attachments/assets/1ae537df-5020-403a-ae9f-7f56c6c43ba0" />

### Football

Live scores, standings and your team's form for **Serie A**, **Premier League**, **LaLiga** and **Saudi Pro League**.

```
<iframe src="https://gnzo3e.github.io/xeneon-edge/serie-a/?team=inter"></iframe>
```

#### Features

- **Matchday:** every match in the round, with live scores and minutes, final results and kick-off times.
- **Standings:** the league table, with Champions League, Europa League, Conference League and relegation places marked.
- **Your team:** last five results, next match, points gap to the leader, goals, and home vs away record.
- **Title race:** points and league position by round for the top four and your team.
- **Switch league:** tap the league name on the Matchday panel.
- **Switch team:** tap the team name on the Standings or Your team panel.
- **Remembers your choices:** your league and team stay picked after a restart.
- **Fits every iCUE size:** the layout adjusts for S, M, L and XL, horizontal or vertical.
- **Works offline:** shows the last saved data straight away, then updates.
- **Live updates:** refreshes every 2 minutes around match time, every 5 minutes otherwise, and pauses while the widget is hidden.

#### Using it

Tap a panel to see its next view:

| Panel | Views |
|---|---|
| Matchday | current / previous / next round |
| Standings | top half / bottom half |
| Your team | form / home vs away |
| Title race | points / position |

On smaller sizes a card holds two panels, and tapping moves on to the second one.

#### Options

Add these to the end of the URL, e.g. `?league=premier-league&team=ARS`.

| Option | Example | What it does |
|---|---|---|
| `league` | `serie-a`, `premier-league`, `laliga`, `saudi-pro-league` | The league to start with. Default is `serie-a`. |
| `team` | `JUV`, `INT`, `ARS`, `RMA` | The team to start with: its 3-letter code or name. |
| `panels` | `matchday,table` | Show only these panels, in this order: `matchday`, `table`, `team`, `race`. |
| `rotate` | `20` | Move every panel to its next view every 20 seconds. |
