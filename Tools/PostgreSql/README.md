---
icon: database
expanded: false
order: 2000
---

# PostgreSQL

## Docker

| Command | Description |
|----------------|----------|
| docker exec dp_database pg_dump -U postgres procurements -n dp --exclude-table=dp.raw_data > dump.sql | Creating dump |
| \d public.actor | Show database details |
| \d | Show all tables |
| psql -U postgres -d table -p 5432 | Log in into database |
