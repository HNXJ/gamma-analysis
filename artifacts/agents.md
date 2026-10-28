# agents

World state: event ledger and reputation, derived from immutable evidence.

## Layout

- `src/`, `docs/`, `schemas/`, `tests/`, `tournaments/` hold only `.gitkeep`. `artifacts/archive/` retired files.

## Build and test

No build. Root layout check (needs a jynx-engine checkout): `python <jynx-engine>/src/scripts/check_shared_root.py .` prints `OK`.

Gate: the root layout check; read its last line.

## Git

- Work on `_temp_<name>` branches; PR to `main`. No direct push to `main`.
- Stage exact paths; never `git add .` or `-A`.
- Never commit `.env`, tokens or keys.
