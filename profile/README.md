## DBGorilla

AI-native database operations.  We build autonomous agents that detect, explain, validate, and resolve database problems before they impact users.

Every recommendation is proven on a clone of your actual database before it touches production.

### Open Source

| Repo | What it does |
|------|-------------|
| [pathological-storefront](https://github.com/dbgorilla/pathological-storefront) | A Postgres database built to be wrong on purpose: 699 deliberate defects, each written down and counted, so a tool that claims to find problems can be scored. |
| [pg_stats_backport](https://github.com/dbgorilla/pg_stats_backport) | Postgres 18's statistics restore functions for Postgres 13 to 17, so `pg_dump --statistics-only` output loads on older servers unchanged. |
| [openapi-cli4ai](https://github.com/dbgorilla/openapi-cli4ai) | Give your AI agent a CLI for any REST API.  Point it at an OpenAPI spec.  Pull-based discovery, not prompt stuffing. |
| [dbgorilla-cli](https://github.com/dbgorilla/dbgorilla-cli) | The DBGorilla CLI.  Sign in to a DBGorilla deployment and connect Claude Code via MCP in three commands.  `brew install dbgorilla/tap/dbgorilla` |
| [homebrew-tap](https://github.com/dbgorilla/homebrew-tap) | Homebrew formulas for DBGorilla tools. |

### Who we are

Our founders Chris Lalonde and Stephen Nolan started working together in 2013, grew a database-as-a-service platform from zero to global scale.  DBGorilla is what comes next -> AI agents that operate your databases so your engineers do not have to.

### Links

- [dbgorilla.com](https://dbgorilla.com)
- [Blog](https://dbgorilla.com/blog)
