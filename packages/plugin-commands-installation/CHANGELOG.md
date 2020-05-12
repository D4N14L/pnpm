# @pnpm/plugin-commands-installation

## 2.0.0-alpha.6

### Major Changes

- da091c71: Remove state from store. The store should not store the information about what projects on the computer use what dependencies. This information was needed for pruning in pnpm v4. Also, without this information, we cannot have the `pnpm store usages` command. So `pnpm store usages` is deprecated.

### Patch Changes

- Updated dependencies [3f73eaf0]
- Updated dependencies [ecf2c6b7]
- Updated dependencies [da091c71]
- Updated dependencies [9fbb74ec]
  - @pnpm/plugin-commands-rebuild@2.0.0-alpha.4
  - supi@0.39.0-alpha.6
  - @pnpm/package-store@9.0.0-alpha.4
  - @pnpm/store-connection-manager@0.3.0-alpha.4
  - @pnpm/types@6.0.0-alpha.0
  - @pnpm/outdated@7.0.23-alpha.2
  - @pnpm/cli-utils@0.4.5-alpha.1
  - @pnpm/config@8.3.1-alpha.1
  - @pnpm/find-workspace-packages@2.2.2-alpha.1
  - @pnpm/manifest-utils@1.0.1-alpha.0
  - @pnpm/pnpmfile@0.1.9-alpha.0
  - @pnpm/resolver-base@7.0.1-alpha.0
  - @pnpm/sort-packages@1.0.10-alpha.1
  - @pnpm/filter-workspace-packages@2.0.15-alpha.1

## 2.0.0-alpha.5

### Patch Changes

- supi@0.38.30-alpha.5

## 2.0.0-alpha.4

### Patch Changes

- Updated dependencies [b5f66c0f2]
  - @pnpm/constants@4.0.0-alpha.0
  - @pnpm/package-store@9.0.0-alpha.3
  - @pnpm/plugin-commands-rebuild@2.0.0-alpha.3
  - supi@0.39.0-alpha.4
  - @pnpm/config@8.3.1-alpha.0
  - @pnpm/find-workspace-packages@2.2.2-alpha.0
  - @pnpm/outdated@7.0.23-alpha.1
  - @pnpm/store-connection-manager@0.2.32-alpha.3
  - @pnpm/cli-utils@0.4.5-alpha.0
  - @pnpm/sort-packages@1.0.10-alpha.0
  - @pnpm/filter-workspace-packages@2.0.15-alpha.0

## 2.0.0-alpha.3

### Patch Changes

- f453a5f46: Update version-selector-type to v3.
- Updated dependencies [c207d994f]
- Updated dependencies [f453a5f46]
  - @pnpm/package-store@9.0.0-alpha.2
  - supi@0.39.0-alpha.3
  - @pnpm/plugin-commands-rebuild@1.0.11-alpha.2
  - @pnpm/store-connection-manager@0.2.32-alpha.2
  - @pnpm/outdated@7.0.23-alpha.0

## 2.0.0-alpha.2

### Major Changes

- 9e2a5b827: `pnpm r` is not an alias of `pnpm remove`.

### Patch Changes

- Updated dependencies [2e8ebabb2]
  - supi@0.39.0-alpha.2

## 1.3.0-alpha.1

### Minor Changes

- 4f62d0383: Executables are saved into a separate directory inside the content-addressable storage.

### Patch Changes

- Updated dependencies [4f62d0383]
  - @pnpm/package-store@9.0.0-alpha.1
  - supi@0.39.0-alpha.1
  - @pnpm/store-connection-manager@0.2.32-alpha.1
  - @pnpm/plugin-commands-rebuild@1.0.11-alpha.1

## 1.2.4-alpha.0

### Patch Changes

- Updated dependencies [91c4b5954]
  - @pnpm/package-store@9.0.0-alpha.0
  - @pnpm/store-connection-manager@0.3.0-alpha.0
  - supi@0.39.0-alpha.0
  - @pnpm/plugin-commands-rebuild@1.0.11-alpha.0

## 1.2.4

### Patch Changes

- Updated dependencies [760cc6664]
  - supi@0.38.30
  - @pnpm/plugin-commands-rebuild@1.0.11

## 1.2.3

### Patch Changes

- 907c63a48: Dependencies updated.
- 907c63a48: Dependencies updated.
- Updated dependencies [907c63a48]
- Updated dependencies [907c63a48]
- Updated dependencies [907c63a48]
- Updated dependencies [907c63a48]
- Updated dependencies [907c63a48]
- Updated dependencies [907c63a48]
- Updated dependencies [907c63a48]
  - supi@0.38.29
  - @pnpm/outdated@7.0.22
  - @pnpm/store-connection-manager@0.2.31
  - @pnpm/package-store@8.1.0
  - @pnpm/plugin-commands-rebuild@1.0.10
  - @pnpm/filter-workspace-packages@2.0.14
  - @pnpm/cli-utils@0.4.4
  - @pnpm/find-workspace-packages@2.2.1
