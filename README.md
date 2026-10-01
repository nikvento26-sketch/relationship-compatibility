# Relationship Compatibility Dashboard

Interactive relationship compatibility dashboard with:

- Online sign-in and account-based cloud saving
- Supabase-backed dashboard data storage
- Browser backup through local storage and JSON export/import
- Editable profiles, score matrix, scenarios, trends, finance, and dashboard setup
- Comparison analytics and printable report generation

## Hosting

The site is designed to run as a static GitHub Pages website. `index.html` is the complete application.

## Online storage

The frontend uses the Supabase publishable key only. Row Level Security is enabled on the Supabase table so dashboard records are restricted to the signed-in account that owns them.
