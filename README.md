# pnpm-test
## Without node-hoisted=true in .npmrc
1. Run `pnpm i`
2. Run `pnpm rebuild`
3. Notice the native node-mac-permissions package rebuilds

## With node-hoisted=true in .npmrc
1. Run `pnpm i`
2. Run `pnpm rebuild`
3. Notice the native node-mac-permissions package doesn't rebuild