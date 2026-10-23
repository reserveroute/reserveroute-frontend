# ReserveRoute — frontend

Open-source planning for Stellar sponsored-reserve transfers and removals. The first adapter supports credit trustlines, with explicit blockers and unsigned transaction preparation.

Run npm run dev after backend npm ci, then open http://127.0.0.1:4340. The UI loads samples, imports JSON, captures public testnet accounts, reviews blockers/history, refreshes state and downloads unsigned XDR/evidence. Run npm test for proxy/API integration.

Read [INTEGRATION.md](INTEGRATION.md) for the connected setup, trust boundaries and supported scope. Components: [engine](https://github.com/reserveroute/reserveroute-engine), [backend](https://github.com/reserveroute/reserveroute-backend), [frontend](https://github.com/reserveroute/reserveroute-frontend), [cli](https://github.com/reserveroute/reserveroute-cli), [fixtures](https://github.com/reserveroute/reserveroute-fixtures).

MIT licensed. Local testnet MVP, not a complete sponsorship inventory or production signing service.
