# @ttionya/tsconfig

> Shared TypeScript config for my projects.

Configure grouping by category, see full configuration options [here](https://www.typescriptlang.org/tsconfig).

<br>

## Required

- NodeJS >=14.18.0
- TypeScript ^4.7.0

<br>

## Install

```bash
# NPM
npm i -D @ttionya/tsconfig

# PNPM
pnpm add -D @ttionya/tsconfig
```

<br>

## Usage

### Node (CommonJS)

```json
{
  "extends": "@ttionya/tsconfig/tsconfig.node.json",
  
  "compilerOptions": {
    "baseUrl": ".",
    "outDir": "./lib"
  }
}
```

### Node (ESM)

```json
{
  "extends": "@ttionya/tsconfig/tsconfig.esm.json",
  
  "compilerOptions": {
    "baseUrl": ".",
    "outDir": "./esm"
  }
}
```

<br>

## License

MIT
