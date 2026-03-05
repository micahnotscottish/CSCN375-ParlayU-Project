This is a group project for CSCN375 - Human Computer Interaction

## Data configuration

The user dashboard now pulls its market and bet data from an external JSON file so you can add or edit entries without touching the HTML or JS code.  

- File: `data/data.json`  
- Each market object may include these additional fields:  
  - `description`: longer text shown on the market detail page.  
  - `comments`: array of `{ user, text }` entries that will appear when viewing a single market.  
  - `defaultStake`, `odds`, and `closes` are also used.  
- Click the middle panel of a market card to open `market.html?idx=N` for more details and comments.  
  The detail page also lets you place Over/Under bets using the same two‑sided card layout as on the dashboard.  

Reload the page (via a simple HTTP server) to see changes take effect.  

