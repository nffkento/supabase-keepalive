# Supabase Keep-Alive

GitHub Actions cron that pings the Supabase REST API every 4 days to prevent the free-tier project from pausing due to inactivity.

## Setup

Add the following secrets to this repository:

| Secret | Description |
|---|---|
| `SUPABASE_URL` | Supabase project URL (e.g. `https://xxxxx.supabase.co`) |
| `SUPABASE_ANON_KEY` | Supabase anonymous/public key |

## Target Project

- **Supabase Project**: Inventory-Management
