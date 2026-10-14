# Cricket Arena · Realistic Cricket

T20, T10, a 5-over Blitz or a Super Over between fictional sides, from over the batter's shoulder or the classic broadcast view. See where the ball will pitch, hold a direction and time your shot as the ring closes; place a marker on the length bands and hit the green on the run-up meter. Swing, seam and spin off green, flat or dusty pitches, diving fielders, run outs, DRS ball-tracking and replays. Practice nets, the CPU or a friend online.

Built with three.js · Ball physics · Online 1v1. Part of [Shreyansh Sharan's portfolio](https://shreyanshsharan.com/), split into its own site.

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
- Press when the ring turns green: `J` defend · `K` along the ground · `L` lofted · `H` leave
- Hold `Shift` front foot · `Space` back foot · `T` charge the spinner
- Calls: `R` yes · `F` no · `G` wait. On a phone, the thumb pad and buttons do the same
- `WASD` or tap the pitch to place the marker · `Space` run in, `Space` again as the needle crosses the green on the arc (the bright middle swings late)
- `G` field editor: drag fielders to named positions under the powerplay rules · `F` preset · `V` over/round the wicket
- Pick a direction with `W` `A` `S` `D` (8 ways, or the pad). `Shift` front foot, `Space` back foot: drive, cut, pull, hook, sweep, flick.
- Calls: `R` yes, `F` no, `G` wait. `I` instant replay.
- Aim the marker with `W` `A` `S` `D` or by tapping the pitch: the bands are yorker, full, good and short.
- `G` field editor, `F` next field preset, `V` round the wicket. While they run, `J` throws to the keeper and `L` to the bowler.

## Ads and gear

Optional AdSense and Amazon affiliate IDs come from environment variables (see `.env.example`). Leave them empty and
no ad or shop code loads.

## Credits

Asset sources and licences: [CREDITS.md](CREDITS.md).
