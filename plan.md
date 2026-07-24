# Da Nang – Hoi An – Ba Na Hills Trip Plan (6 days / 5 nights)

## Known inputs
- Arrival: EK370, lands Da Nang (DAD) 21:50 (Day 1)
- Departure: EK371, leaves 23:30 (Day 6); traveler wants to be at airport by 21:00 (2.5 h early)
- Hotels: N1 Airport Homestay Da Nang · N2 Mercure French Village Bana Hills · N3 Royal Riverside Hoi An · N4–5 Bluesun Danang Beach (free airport car — draft arrangement message)
- Profile: light adventure + amazing food, high-Google-rating / local-recommended eateries
- Must-visits: Hoi An Old Town + Night Market, My Khe Beach, basket boat, Vinpearl River Safari Nam Hoi An, Dragon Bridge, Marble Mountains, good cafes
- Deliverable: ONE self-contained HTML page with pictures + minute-by-minute timeline + clickable Google Maps links + alternatives list + two hotel message templates
- Constraints: verify nothing is closed on the planned day; Dragon Bridge fire show only Fri/Sat/Sun ~21:00 (verify); optimize transport cost (bus where sensible, Grab otherwise)

## Assumption (flag to user)
No travel dates given → plan built as Day 1 (Wed) … Day 6 (Mon) so the Da Nang beach nights include a Fri/Sat/Sun for the Dragon Bridge fire show. Fully day-shiftable; noted in HTML.

## Stage 1 — Research (AgentSwarm, explore agents, parallel)
1. Flights + Da Nang airport late-night arrival logistics
2. Mercure Bana Hills check-in logistics (cable car, luggage, last car up)
3. Ba Na Hills attractions/hours/prices/food
4. Hoi An Old Town, Night Market, lantern boats, top cafes + restaurants
5. Cam Thanh basket boat + Vinpearl River Safari Nam Hoi An opening status 2025–2026
6. Da Nang sights: My Khe, Marble Mountains, Dragon Bridge show schedule, Son Tra, rainy-day alternatives
7. Da Nang food + cafes (high-rating, food-first)
8. Transport matrix with 2025–2026 prices for every leg (bus vs Grab)
9. Hotel verification (late check-in, airport shuttle) + verified working image URLs

## Stage 2 — Itinerary assembly (orchestrator)
- Build minute-by-minute timeline per day, cost-optimized route, alternatives list, two hotel messages.

## Stage 3 — HTML build (coder agent)
- Single file `danang-hoian-trip-plan.html` in workspace: day timeline cards, images (curl-verified URLs), Google Maps search links per stop, transport/cost badges, food picks, alternatives, hotel message copy blocks, travel-guide tips.
- Coder must curl-check every image URL and fix broken ones.

## Stage 4 — Validate & deliver
- Spot-check timeline feasibility + closure conflicts; deliver file link + both hotel messages in chat.
