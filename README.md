# Save Point

A lightweight PlayStation playtime tracker. Keep a library of games, time live play sessions, log past sessions, see weekly and lifetime hours, and export your history as CSV.

## Run locally

Run a local web server from this directory so the included game catalog can load:

```sh
python3 -m http.server 4173
```

Then visit <http://localhost:4173>.

Your library and sessions are saved in the browser's local storage. This is a manual tracker: it does not sign in to PlayStation Network or retrieve playtime automatically.

The alphabetical PS5 title catalog is based on the released games in [Wikipedia's list of PlayStation 5 games](https://en.wikipedia.org/wiki/List_of_PlayStation_5_games), retrieved October 3, 2026. The list is provided under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/); its source and license are also recorded in `ps5-games.json`. New or unlisted games can still be entered as custom titles.
