# GA Schedule — Agent Guide
Stack: HTML + Vanilla JS + Tailwind CSS + Supabase  
Host: GitHub Pages (single file: index.html)  
DB: Supabase (see docs/schema.sql)

## Rules
- Never split into multiple JS files — keep single index.html
- Use Tailwind CDN, not build process
- All Supabase calls use supabase-js CDN
- Thai language UI labels

## Features in scope
- Task CRUD, WBS hierarchy, Gantt SVG
- Dependency types: FS / SS / FF / SF
- Status: Not Started / In Progress / Completed / Cancelled
- Export CSV (UTF-8 BOM for Thai Excel)
