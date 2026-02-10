# Agent systems: a practical checklist

## What usually breaks first

- cost runaway (unbounded browsing / tool loops)
- missing audit trail (no replay of decisions)
- unclear triggers (agent spams or stays silent)

## What to design upfront

- permissions & scopes (read vs write)
- rate limits / budgets (tokens, time, requests)
- state model (memory, cache, durable notes)
- escalation policy (when to ping human)
