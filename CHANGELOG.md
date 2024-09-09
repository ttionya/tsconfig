# Changelog

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
