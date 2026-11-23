# The Model Picks website: instructions for Claude

- This public repo holds only the website (index.html, served by GitHub Pages from main). Never add model code, data, API keys or anything from the private jackdlongmore/betting-model repo except the published picks and record.
- Weekly update: after a slate card is final, update index.html (this week's plays, radar, staying away, record, archive) on a new branch named site/<yyyy-mm-dd> and open a pull request titled "Site update: <week label>". Never push site changes straight to main: the user approves by merging.
- The page has two tiers: Best bets (1 unit, the model plus at least two independent signals, counted in the record) and Leans (½ unit at most, shown for information, tracked separately). The record counts best bets only (bet_log rows noted "User's bet" are excluded), graded at the line taken, wins and losses alike.
- Keep the design (navy #0f1c2e, mint #7fd1a8, Barlow Condensed + Inter) and the responsible-gambling footer.
