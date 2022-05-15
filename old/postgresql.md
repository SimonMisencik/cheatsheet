---
title: PostgreSQL
---

# PostgreSQL

## PostgreSQL command

| Command | Description |
|----------------|----------|
| docker exec dp_database pg_dump -U postgres procurements -n dp --exclude-table=dp.raw_data > dump.sql | Creating dump |
