YYYY-MM-DD | Dn | minutes | did | learned | blocker | next
2026-11-07 | D1 | A1 audit: Google "Eshan Shikarkhane supabase" = 0 (Missing: supabase). Two-click count: 3/6
2026-11-07 | D1 | 90 | A1 audit, repo, supabase init/start, docker ps vs prediction | | none | W0 Sun: community reading, Mon announce
docker ps: predicted 7–8 containers, actual 13. Surprise: Mailpit.
2026-11-08 | D2 | mental models: RLS lives in Postgres because it's the one place every path goes through, so the rule is written once and no door can skip it; in app code, one missed copy leaks every user's data.
2026-11-08 | D2 | mental models: One gateway because it's the single public door: shared checks (keys, CORS, rate limits) happen once, and the 5 services stay private behind it.
