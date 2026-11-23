# Smash Kodoku #10 — Stage Striking prototype

## Included
- Single-browser interactive prototype.
- Heads/tails coin toss to assign the first striker.
- Game 1 starter pool and 1–2–1 striking sequence.
- Games 2–3: winner bans three; opponent selects a counterpick.
- DSR check against previously selected stages.
- Action history and reset controls.

## Important limitation
This prototype is local to one browser. It does NOT synchronize two players on separate devices, authenticate players, or persist a tournament-wide match database. Do not use it as a live shared room yet.

## Try it
Open `index.html` in a modern browser. No installation is needed.

## Next step for a shared version
Deploy the frontend (for example, on Vercel) and connect a realtime database/backend (for example, Supabase). Each set should have a unique room code and server-side validation of turns, bans, picks, and DSR. The current prototype is a functional interaction demo, not that production multiplayer system.
