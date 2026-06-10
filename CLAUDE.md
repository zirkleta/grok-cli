# grok-cli

xAI Grok CLI (Bun + TypeScript).

## Run
- `bun run dev` | binary: `bun run build:binary`

## Verify
- `npm run typecheck && npm run test` (vitest) and `npm run lint` (biome)

## Gotchas
- Upstream installer overwrites ~/.local/bin/agent (Cursor collision) — see memory reference-grok-cli-installer-symlink-shadow
