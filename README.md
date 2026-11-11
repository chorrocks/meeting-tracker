# Meeting Cost Ticker

A self-contained meeting cost calculator. Open `index.html` directly in a browser; no installation, network access, or build step is required.

Alternatively, from this directory run `python -m http.server 8000 --bind 0.0.0.0` and visit port 8000 locally. Use this method in managed browsers that block opening local files.

Enter the number of people and average hourly cost in USD, then select Start. Pause freezes elapsed time and cost; Resume continues the session. Reset clears time and cost, keeps your inputs, and unlocks setup. Rates stay fixed during a session. The counter uses elapsed time rather than counting timer callbacks so background tab throttling does not lose time. Reloading or closing the page clears the session.

All styles, icons, and scripts are included in the HTML file. No requests, accounts, tracking, or external assets.
