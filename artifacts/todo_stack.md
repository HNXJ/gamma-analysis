# todo stack

Top = next. Gate: root layout check (see `agents.md`).

- T-1 Add an event ledger schema in `schemas/` and a test that rebuilds world state from a fixture event list. Closes when: `python -m pytest tests -q` reports at least 1 passed, 0 failed. Blocked by: none.
- T-2 Triage open issues #1 to #4 (inherited; #4 Izhikevich fitting framework likely belongs in jynx-lab). Closes when: `gh issue list -R HNXJ/jynx-world --state open --json number -q length` prints 0. Blocked by: none.
