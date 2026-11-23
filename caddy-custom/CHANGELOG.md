## What’s changed

- Caddy-custom starts immediately and xcaddy-builder runs in the background.
- Caddyfile is validated before startup and automatically fall back to `--resume` (last known good autosave.json) while new plugins compile.
- Added scheduled update checks option (default: 24h, 0 to disable).
- Check for Home Assistant app updates.
