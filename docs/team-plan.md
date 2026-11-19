# Student Team Execution Plan — bazaar-commerce

Team: student team with classmates + faculty advisor, verified by university edu.cn email.
Repo: fork of https://github.com/Cubitrek/bazaar-commerce

## Timeline — 30 days
Week 1 (Days 1-7): Fork repo, set up stack, reproduce #3 on clean DB — 31/34 today, document failing checks 32-34. Advisor reviews fork.
Week 2 (Days 8-14): Fix #3 CSV determinism, get to 34/34 on clean DB. Target: 4 PRs.
Week 3 (Days 15-21): WhatsApp inbound replies — "yes" actually confirms the order, state machine transitions. Target: 5 PRs.
Week 4 (Days 22-30): Courier outcomes feeding the RTO score, then start #1 free-delivery leak. Final review + upstream PRs. Target: 6 PRs.

## Commit frequency
- Devin Bot: 1-2 PRs per working day when active
- Humans: review every Bot PR within 24 hours, each member commits 3-4 times per week
- Team: 2 syncs per week, advisor check-in once per week
- No merge to the ledger without human review

## Total
~15 PRs in 30 days, all gated by tests — 31/34 → 34/34 first, then WhatsApp tests green before courier webhooks.
