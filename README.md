# gnzo3e.github.io

## Xeneon Edge widgets

Widgets for the Corsair Xeneon Edge, made for iCUE's iFrame widget. Paste the URL into an iFrame widget in iCUE.

### Serie A

```
<iframe src="https://gnzo3e.github.io/xeneon-edge/serie-a/?team=inter"></iframe>
```

| Param | Example | Meaning |
|---|---|---|
| `team` | `JUV`, `INT`, `MIL`, `NAP` | The team to follow. Use its 3-letter code or name. Default is `JUV`. |
| `panels` | `matchday,table` | Which panels to show, and in what order: `matchday`, `table`, `team`, `race`. Useful for smaller iCUE slots. |

Tap a panel to cycle its view:

| Panel | Views |
|---|---|
| Matchday | current / previous / next round |
| Table | positions 1–10 / 11–20 |
| Your team | form / home vs away |
| Title race | points / position |
