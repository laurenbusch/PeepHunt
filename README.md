# Easter Peep Hunt 🐣

A fun, browser-based Easter egg hunt game. Set up prizes and poems, hand out numbered peeps, and let players enter their peep numbers to reveal what they won.

## How to Play

### Setup
1. Open `index.html` in any web browser — no installation required.
2. Set the **total number of peeps** (numbered eggs) in the hunt.
3. Add **prizes** with quantities (e.g. `5` × `$5 bill`, `3` × `Candy Bar`).
   - Any prize with `$` in the name is treated as cash and totaled in the final results.
4. Optionally check **Fill remaining peep numbers with poems** to assign one of 42 built-in joke poems to every unclaimed slot.
5. Click **Begin game 🐣**.

### During the Game
- Enter the current player's name when prompted.
- Type in a peep number to reveal its prize.
- Use **Change player** to switch between players or add new ones mid-game.
- Use **Exit game** to end the hunt and see results.

### Results
- Winners are displayed in columns (up to 5), one per player.
- Every prize category is shown for every player — including `0` for categories they didn't win.
- Cash prizes are summed into a single **Cash** total.
- 🏆 appears next to the category leader(s) for each prize type.
- Use **Save results to spreadsheet** to export a `.xlsx` summary.

## Features

- Fully offline — runs as a single HTML file with no server needed
- 42 built-in Easter-themed joke poems that cycle through automatically
- Multi-player support with instant player switching
- Cash prize aggregation (any prize name containing `$`)
- Trophy indicators for category leaders (ties included)
- Export to Excel spreadsheet
- Easter color scheme 🌸

## Hosting on GitHub Pages

1. Rename the file to `index.html`
2. Push to a GitHub repository
3. Go to **Settings → Pages** and set the source to your main branch
4. Your game will be live at `https://yourusername.github.io/repo-name`

## License

MIT — see [LICENSE](LICENSE) for details.
