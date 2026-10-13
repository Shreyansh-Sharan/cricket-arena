# Cricket Arena · Realistic Cricket

T20, T10, a 5-over Blitz or a Super Over between fictional sides, from over the batter's shoulder or the classic broadcast view. See where the ball will pitch, hold a direction and time your shot as the ring closes; place a marker on the length bands and hit the green on the run-up meter. Swing, seam and spin off green, flat or dusty pitches, diving fielders, run outs, DRS ball-tracking and replays. Practice nets, the CPU or a friend online.

Built with three.js · Ball physics · Online 1v1. Part of [Shreyansh Sharan's portfolio](https://shreyansh-sharan.github.io/shreyanshsharan-portfolio/), split into its own site.

```bash
npm install
npm run dev      # http://localhost:5173
npm run build    # production build in dist/
npm run lint     # oxlint
```

The site is a single page: `#/` is the game's menu, and the same query parameters the portfolio used still work
(for example `#/?auto=...` to skip the menu, `#/?join=CODE` for an invite link).

## Controls

- Hold a direction: `W` `A` `S` `D` or arrows (8 ways, none = natural shot). The wedge on the ground shows where it goes
- Press when the ring turns green: `J` defend · `K` along the ground · `L` lofted
- Hold `Shift` front foot · `Space` back foot · `T` charge the spinner
- `R` run · `F` stay / back to the crease
- `1`–`6` delivery: seam, swing, bouncer, yorker, slower ball; off-break, leg-break, googly, arm ball, top-spinner
- `WASD` place the pitch marker · `Space` run in, `Space` again in the green
- `F` field: attacking, normal, defensive, death · `V` over/round the wicket
- send()}> `` ov ·
- Hold a direction with `W` `A` `S` `D` or the arrows: the wedge on the ground shows where the shot will go. No direction plays the natural shot.
- Hold `Shift` for the front foot, `Space` for the back foot. Then `R` runs and `F` sends him back.
- Pick a delivery with `1`–`6` (or `Q`/`E`). Its name shows big on the right.
- Place the yellow marker with `W` `A` `S` `D`. The bands on the pitch are the lengths: yorker, full, good, short.
- Run in and release. `Space` starts the run-up; press `Space` again when the needle is in the green. Too late and it is a no-ball.
- `F` changes the field, `V` goes round the wicket. While they run, `J` throws to the keeper and `L` to the bowler.

## Ads and gear

Optional AdSense and Amazon affiliate IDs come from environment variables (see `.env.example`). Leave them empty and
no ad or shop code loads.

## Credits

Asset sources and licences: [CREDITS.md](CREDITS.md).
