# @ttionya/tsconfig

[![npm](https://img.shields.io/npm/v/@ttionya/tsconfig?label=NPM&logo=npm)](https://www.npmjs.com/package/@ttionya/tsconfig) [![npm](https://img.shields.io/npm/dm/@ttionya/tsconfig?label=Downloads&logo=npm)](https://www.npmjs.com/package/@ttionya/tsconfig) [![npm](https://img.shields.io/npm/l/@ttionya/tsconfig?label=License&logo=npm)](https://github.com/ttionya/tsconfig/blob/master/LICENSE)

> Shared TypeScript config for my projects.

Configure grouping by category, see full configuration options [here](https://www.typescriptlang.org/tsconfig).

<br>

## Required

- NodeJS `>=18.12.0`
- TypeScript `^5.0.0`

**IMPORTANT:** This branch only supports Node 18 LTS or higher and TypeScript 5. Switch to the [`v1`](https://github.com/ttionya/tsconfig/tree/v1) branch that supports Node 14 LTS and TypeScript 4.7+.

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
  "extends": "@ttionya/tsconfig/tsconfig.commonjs.json",
  
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
