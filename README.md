# Preact on Bun

Example [Preact](https://preactjs.com/) app running on [Bun](https://bun.sh/). Preact is a small, fast alternative to React with the same modern API. Bun is a fast all-in-one JavaScript runtime and package manager compatible with Node.js.

## Deploy settings

| Field | Value |
| --- | --- |
| Build | Static site — Railpack build |
| Single-page application (SPA) | off |
| Project directory | `/` |
| Output directory | `/dist` |
| Install command | leave empty |
| Build command | leave empty |
| Health check path | `/` |

## <a name="dev"></a>Run locally

```bash
# install dependencies
bun install

# run in development mode
bun run dev

# build for production
bun run build
```
