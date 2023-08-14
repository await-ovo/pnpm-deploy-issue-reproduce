# deploy

1. `pnpm add -g pnpm@8.6.10`
2. `pnpm install`
3. `pnpm --filter foo deploy ./pruned`

You can see that there are no root project dependencies in `pruned/node_modules`