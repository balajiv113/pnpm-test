# pnpm-test
## Without node-linker=hoisted in .npmrc
1. Run `pnpm i`
2. Run `pnpm rebuild`
3. Notice the native node-mac-permissions package rebuilds

## With node-linker=hoisted in .npmrc
1. Run `pnpm i`
2. Run `pnpm rebuild`
3. Notice the native node-mac-permissions package doesn't rebuild
