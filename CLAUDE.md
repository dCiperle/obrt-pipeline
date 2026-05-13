# obrt-pipeline

## Project

obrt-pipeline is an internal tooling repository. It stores reusable
skills, agent patterns, and documentation that double as a proof of
competence and a test ground for new agent designs.

Client code for paid pilots lives in a separate repository, not here.

## Business context

Maintained by David Ciperle. The surrounding business is AI automation
for Slovenian manufacturing and technical service companies with 5 to
50 employees, primarily in Gorenjska and central Slovenia.

Pricing model: pilot 500 to 1,500 EUR plus retainer 150 to 300 EUR per
month. 90-day target (through 2026-08-09): 3 paying clients.

## Tech stack

Python 3.12, planned from Week 5 onward. Current state: empty scaffold
with markdown skill files and documentation. Planned stack: Claude
Agent SDK, FastAPI, FastMCP for client-facing MCP servers.

## First user (dogfood)

Jože Ciperle s.p., mechanical and plumbing installations, the author's
father. The `racuni-ciperle` skill (currently lives in the Cowork
project; integration into this repo is planned after Week 5) issues 10
to 20 production invoices per month.

## Code style

Documentation (README, CONTRIBUTING, CLAUDE.md, code comments) is
written in English. User-facing strings (invoices, quotes for the
father's customers) are written in Slovenian. Use the Slovenian
decimal comma in Slovenian text.

## Critical rules

- On invoices for the father's business, always use only
  "JOŽE CIPERLE s.p." as the legal name. Never use "ZAKLJUČNA
  GRADBENA DELA" or "J&D CIPERLE".
- This is an internal tooling repo. Client code for future pilots
  (after the first signed pilot) goes into a separate repo, not this
  one.

## Where to find things

(To be filled in as the project grows.)
