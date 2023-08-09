# @ttionya/tsconfig

> Shared TypeScript config for my projects.

Configure grouping by category, see full configuration options [here](https://www.typescriptlang.org/tsconfig).

<br>

## Required

- NodeJS >=14.18.0
- TypeScript ^4.7.0

**IMPORTANT:** Switch to the [`master`](https://github.com/ttionya/tsconfig) branch that supports Node 18 LTS or higher and TypeScript 5.

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
    "outDir": "./lib"
  }
}
```

### Node (ESM)

```json
{
  "extends": "@ttionya/tsconfig/tsconfig.esm.json",
  
  "compilerOptions": {
    "outDir": "./esm"
  }
}
```

<br>

## License

MIT
