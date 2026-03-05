This is a group project for CSCN375 - Human Computer Interaction

## Data configuration

The user dashboard now pulls its market and bet data from an external JSON file so you can add or edit entries without touching the HTML or JS code.  

- File: `data/data.json`  
- Adjust the `markets` array to add new markets or change odds/close dates.  
- Update `balance` or `recentBets` as needed for testing.  

Reload the page (via a simple HTTP server) to see changes take effect.

