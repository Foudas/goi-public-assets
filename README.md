# GOI Public Assets

Public, client-facing portfolio PDFs for Growth Of Influence.

## Why this repo is public

These files are published so an automated proposal system can fetch them over HTTPS
at submission time and attach them directly. Files served from
`raw.githubusercontent.com` carry `Access-Control-Allow-Origin: *`, but only for
public repositories, which is the reason this repo is public rather than private.

## Contents

    portfolios/   Client-facing portfolio PDFs

Raw URL pattern:

    https://raw.githubusercontent.com/Foudas/goi-public-assets/main/portfolios/<filename>

## Naming rule

Filenames contain no spaces and no underscores, so that every raw URL is usable
without percent encoding. Use CamelCase, for example
`ChrisAIContentCreationPortfolioSmall.pdf`. Anything added here must follow the
same rule.

## Rules for this repo

Nothing confidential belongs here. Assume every file in this repository is world
readable and permanently cached. Do not add logs, agent prompts, credentials,
config files, contracts, invoices, client data, or anything internal. Public
portfolio PDFs only, added explicitly by name.
