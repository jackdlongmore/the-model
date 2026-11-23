# The Leg Up website: instructions for Claude

The site's name is "The Leg Up" (logo, page title, footer).

- This public repo holds only the website (index.html, served by GitHub Pages from main). Never add model code, data, API keys or anything from the private jackdlongmore/betting-model repo except the published picks and record.
- Weekly update: after a slate card is final, update index.html (this week's plays, radar, staying away, record, archive) on a new branch named site/<yyyy-mm-dd> and open a pull request titled "Site update: <week label>". Never push site changes straight to main: the user approves by merging.
- The page has two tiers: Best bets (1 unit, the model plus at least two independent signals, counted in the record) and Leans (½ unit at most, shown for information, tracked separately). The record counts best bets only (bet_log rows noted "User's bet" are excluded), graded at the line taken, wins and losses alike.
- Best bets show an "Edge vs market" bar and a separate 5-segment confidence bar labeled Solid (3), Strong (4) or Top play (5), with estimated win % vs break-even in small print. Leans get no confidence bar.
- Props section: the prop model's strongest passing and receiving yard props (rushing left out), each with projection vs line gauge, model % vs break-even and best price. Tracked separately, not in the record.
- Keep the design (navy #0f1c2e, mint #7fd1a8, Barlow Condensed + Inter) and the responsible-gambling footer.
