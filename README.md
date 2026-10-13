# IAR Intake prototype

Public, synthetic-only demonstration of the pilot and initiative evaluation module.

Open the demo: https://delgadowgu.github.io/iar-intake-prototype/

## Demonstrating the app

- Use the demo role selector to explore owner, reviewer, council, team lead, and leadership experiences.
- Open Leadership dashboard for the portfolio summaries, filters, boards, and initiative details.
- Open Reviews for formal evaluations. Open Tasks for everyday work, with My tasks as the default. Initiative tasks use the same records.
- Each browser has independent synthetic data. Changes remain in that browser; they are not shared with other visitors.
- Demo roles are walkthrough controls, not authentication. Do not enter real or confidential information.
- Proposed rubric and process settings are demonstration material, not adopted policy.

## Hosting boundary

This repository contains only the compiled static website and this guide. It does not contain source documents, meeting material, local files, credentials, or a Databricks backend.

GitHub Pages serves this public prototype. It is not a production intake service. There is no real sign-in, shared database, Databricks connection, or automated notification delivery.

Source code remains in the local development workspace. This repository is a publication repository, not a source-code backup. Future releases must be rebuilt with Vite base `/iar-intake-prototype/`, checked, and deliberately published here.

## Build verification

Published package prepared October 13, 2026. Lint, TypeScript/production build, and 185 tests in 19 files passed before publication. These checks do not establish production readiness.


## Initiative history example

Open https://delgadowgu.github.io/iar-intake-prototype/#initiative-history/00000000-0000-4000-8000-000000009901 to compare the fictional mentoring plan across three versions, Morgan Lee's original rubric review (32), and Casey Brooks's correction (33). Original inputs, scores, reviewers and dates remain visible. Later initiative changes do not rewrite either review. Existing browser demo history is preserved.
