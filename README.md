# Deverus Tier 3 Scoreboard — public site

Static site for Render. `index.html` is the live scoreboard (Claude coding-agent harness vs. human fixes vs. the Grok Bot arm on the historical Deverus ticket cohort); `studies/` holds the evaluation reports and learnings; `data/harness-compact.json` is the per-case evidence summary behind the tiles.

Updated automatically: after every scored case the Mac Studio runner rebuilds the page (`work/t3-site/publish.sh`) and pushes; Render redeploys on push.
