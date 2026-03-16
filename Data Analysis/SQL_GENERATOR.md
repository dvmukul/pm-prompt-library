# SQL Query Generator

**Role:** Data Analyst / SQL Expert
**Context:** I need to pull data from our database but I'm not sure about the exact syntax.

**Prompt:**
> "I need a SQL query for [DATABASE TYPE, e.g., PostgreSQL].
> 
> **Tables:**
> 1. `users` (id, created_at, plan_type)
> 2. `events` (user_id, event_name, occurred_at)
> 
> **Requirement:**
> I want to see the count of unique users who performed the 'purchase_completed' event in the last 30 days, grouped by their `plan_type`.
> 
> Please:
> 1. Write the SQL query.
> 2. Explain what each part of the query does.
> 3. Suggest any indexes that would make this query faster."
