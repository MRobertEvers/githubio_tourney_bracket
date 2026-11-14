# Kart Cup tournament bracket

**Open it here: https://mrobertevers.github.io/githubio_tourney_bracket/**

A sign-up and bracket page for kart racing tournaments, built to run on a laptop or tablet next to the TV.

- **Sign up** racers by name, then start the tournament.
- **Races** hold up to 4 racers. After each cup, tap the finishers in order and the top 2 move on.
- **The final** awards 1st, 2nd and 3rd place trophies and shows a podium.
- **Mid-tournament changes:** use *Manage racers* to drop someone who leaves, bring them back, rename a seat for a substitute, or add a late racer to a first-round race that hasn't started.
- **Mistakes:** tap a placed racer to undo their result.

Everything is saved in the browser's local storage, so refreshing the page keeps the tournament. It is stored per browser and per device, and private windows may not save it.

The whole app is the single file [`index.html`](index.html). There is no build step and no server; GitHub Pages serves it from the `main` branch.
