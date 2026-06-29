# sealskin-store

Custom Sealskin app store for Serph91P webtop images.

## Apps

| App | Image | Auto-update |
|-----|-------|-------------|
| VS Code | `ghcr.io/serph91p/docker-webtop-vscode:latest` | Manual |
| Plezy | `ghcr.io/serph91p/docker-webtop-plezy` | Release dispatch |
| Streamlink Twitch GUI | `ghcr.io/serph91p/docker-webtop-streamlink` | Release dispatch |

Image repos trigger this store with `repository_dispatch` after successful builds.
