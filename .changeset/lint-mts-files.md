---
"@kachkaev/eslint-config-base": minor
"@kachkaev/eslint-config-next": minor
---

Lint `.mts` files. The generated config blocks were scoped to `.ts` and `.tsx`, so `.mts` files were silently skipped, or failed to parse when another config block matched them.
