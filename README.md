# @ttionya/tsconfig

Shared TypeScript config for my projects.

Configure grouping by category, see full configuration options [here](https://www.typescriptlang.org/tsconfig).

## Require

- TypeScript >=4.7.0
- NodeJS >= 14.18.0

## Install

```bash
pnpm i -D @ttionya/tsconfig
```

<br>

## Usage

### Node (CommonJS)

```json
{
  "extends": "@ttionya/tsconfig/tsconfig.node.json",
  
  "compilerOptions": {
    "outDir": "lib"
  }
}
```

### Node (ESM)

```json
{
  "extends": "@ttionya/tsconfig/tsconfig.node-esm.json",
  
  "compilerOptions": {
    "outDir": "esm"
  }
}
```

### Web

```json
{
  "extends": "@ttionya/tsconfig/tsconfig.node-esm.json",
  
  "compilerOptions": {
    "outDir": "esm"
  }
}
```

## License

MIT
