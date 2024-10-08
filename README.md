```
pnpm add eslint @typescript-eslint/eslint-plugin @mladovic/eslint-config-ts
```

package.json

```
"lint": "eslint './{src,tests}/**/*.ts' --cache",
"lint:fix": "eslint './{src,tests}/**/*.ts' --cache --fix",
"lint:debug": "TIMING=1 eslint './{src,tests}/**/*.ts'"
```
