# Infra samples

These are intentionally generic. They’re here because:
- having a working baseline beats inventing one during a panic
- containerization makes “rebuild from scratch” possible

If you’re on a managed platform, you may not need these.
If you’re self-hosting, you probably do.

- **docker-compose.example.yml** — app + reverse proxy + healthcheck skeleton
- **Caddyfile.example** — simple TLS-terminating proxy (placeholders)
