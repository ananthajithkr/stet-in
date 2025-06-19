---
title: "Projects"
date: "2025-06-19"
author: "ananthajith kr"
draft: false
---

Here is my [github repo](https://github.com/ananthajithkr/)

# Software Projects

1. Zotero Frontend called Easy_Zotero.

This is a lightweight frontend for searching public group libraries in Zotero.

Instead of the heavy official web app, this implementation makes a python backend do fetching items via API, JSON flattening, saving the JSON to SQL base and SQL fs5 based on a schema, and provides an API via FastAPI for the frontend to access. The frontend runs minimal JS to query the fs5 table and then the base table based on the fs5 results. It supports fuzzy search. It then displays the results in a sortable table which also highlights the search terms.

As opposed to the official API which only lets you search a few fields, this frontend queries more fields including the abstract, because the SQL database is an exact replica of all items and fields. You can also do field-specific searches. It is also much lighter on your browser. You may setup a cron job to run the fetching action once a week or so. It requires pyzotero, sqlite3, and uvicorn.

# Hardware Projects

I am tinkering with my old raspi whose USB ports are now kaput. I am going to configure it to run headless and use it for some project; I am just not sure what.