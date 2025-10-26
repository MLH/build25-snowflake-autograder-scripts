# Build 2025 — Snowflake Autograder Scripts

Short, ready-to-run SQL scripts to validate steps in Build 2025 Snowflake workshops.

## What’s here

- `snowflake-intelligence.sql` — Grades the Snowflake Intelligence (AI) lab. 
- `snowflake-dynamic-tables.sql` — Grades the Snowflake Dynamic Tables (DE) lab.

## Prerequisites

- A Snowflake account with a role that can run the checks (ACCOUNTADMIN recommended or equivalent privileges).
- Setup the Autograder that provides the helper function `util_db.public.grader`.

## How to run

You can run these scripts in Snowsight Workspaces.

### Snowsight

1. Open Snowsight and navigate to a Workshpace.
2. Create a new worksheet.
3. Paste the contents of `snowflake-intelligence.sql` or `snowflake-dynamic-tables.sql`.
4. Run all statements step by step to ensure you completed all parts of the lab.

You should see one graded row per step (e.g., AIM1S1, AIM1S2, …) and a final status message when everything passes.

## License

See `LICENSE` for details.
