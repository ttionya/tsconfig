# Changelog

## v3.1.0

### Feature

- Require Node.js `>=20.19.0` and TypeScript `^5.9.0`
- Set `module` from `node16` to `node20`
- Set `target` from `es2022` to `es2023`
- In ESM, removed the option `resolveJsonModule`

### Chore

- Update dependencies
- Bumped `actions/checkout` from 4 to 5 in GitHub Actions
- Replaced `npx` with `pnpm exec` in Husky hooks

<br>

## v3.0.0

### Feature

- Require Node 20 TLS or higher and TypeScript 5

### Chore

- Update dependencies
- Upgrade Node.js version in GitHub Actions from 20 to 22

<br>

## v2.2.0

### Feature

- Remove the option `forceConsistentCasingInFileNames`
- Upgrade `lib` from `es2022` to `es2023`

### Chore

- Update dependencies
- Update the CHANGELOG reference
- Upgrade Node.js version in GitHub Actions from 16 to 20

<br>

## v2.1.0

### Feature

- Add `classic` configuration for CommonJS to resolve the requirement of matching `module` and `moduleResolution` in [TypeScript 5.2](https://devblogs.microsoft.com/typescript/announcing-typescript-5-2/#module-and-moduleresolution-must-match-under-recent-node-js-settings)
- In CommonJS, set the `module` to `Node16`

### Chore

- Update dependencies

<br>

## v2.0.1

### Feature

- In CommonJS, set the `moduleResolution` to `Node16`

<br>

## v2.0.0

### Feature

- Require Node 18 TLS or higher and TypeScript 5

### Chore

- The `npm publish` command will employ the appropriate tag
- Update the CHANGELOG reference

<br>

## v1.2.0

### Feature

- Remove the rules `noUnusedLocals` and `noUnusedParameters`

<br>

## v1.1.0

### Feature

- Update the peerDependencies: `typescript@^4.7.0`

### Chore

- Update the GitHub Actions: `pnpm/action-setup@v2.4.0`

<br>

## v1.0.0

First version.
