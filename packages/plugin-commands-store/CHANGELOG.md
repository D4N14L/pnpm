# @pnpm/plugin-commands-store

## 2.0.0-alpha.4

### Major Changes

- da091c71: Remove state from store. The store should not store the information about what projects on the computer use what dependencies. This information was needed for pruning in pnpm v4. Also, without this information, we cannot have the `pnpm store usages` command. So `pnpm store usages` is deprecated.
- 471149e6: Change the format of the package index file. Move all the files info into a "files" property.
- 9fbb74ec: The structure of virtual store directory changed. No subdirectory created with the registry name.
  So instead of storing packages inside `node_modules/.pnpm/<registry>/<pkg>`, packages are stored
  inside `node_modules/.pnpm/<pkg>`.

### Patch Changes

- Updated dependencies [3f73eaf0]
- Updated dependencies [da091c71]
- Updated dependencies [471149e6]
- Updated dependencies [e3990787]
  - @pnpm/get-context@2.0.0-alpha.1
  - @pnpm/store-connection-manager@0.3.0-alpha.4
  - @pnpm/store-controller-types@8.0.0-alpha.3
  - @pnpm/types@6.0.0-alpha.0
  - @pnpm/cafs@1.0.0-alpha.4
  - @pnpm/cli-utils@0.4.5-alpha.1
  - @pnpm/config@8.3.1-alpha.1
  - dependency-path@4.0.7-alpha.0
  - @pnpm/lockfile-utils@2.0.12-alpha.0
  - @pnpm/normalize-registries@1.0.1-alpha.0
  - @pnpm/pick-registry-for-package@1.0.1-alpha.0

## 2.0.0-alpha.3

### Major Changes

- b5f66c0f2: Reduce the number of directories in the virtual store directory. Don't create a subdirectory for the package version. Append the package version to the package name directory.
- 9596774f2: Store the package index files in the CAFS to reduce directory nesting.

### Patch Changes

- Updated dependencies [9596774f2]
- Updated dependencies [7852deea3]
  - @pnpm/cafs@1.0.0-alpha.3
  - @pnpm/config@8.3.1-alpha.0
  - @pnpm/get-context@1.2.2-alpha.0
  - @pnpm/store-connection-manager@0.2.32-alpha.3
  - @pnpm/cli-utils@0.4.5-alpha.0

## 1.0.11-alpha.2

### Patch Changes

- Updated dependencies [42e6490d1]
  - @pnpm/store-controller-types@8.0.0-alpha.2
  - @pnpm/store-connection-manager@0.2.32-alpha.2

## 1.0.11-alpha.1

### Patch Changes

- Updated dependencies [4f62d0383]
  - @pnpm/store-controller-types@8.0.0-alpha.1
  - @pnpm/store-connection-manager@0.2.32-alpha.1

## 2.0.0-alpha.0

### Major Changes

- 91c4b5954: Using a content-addressable filesystem for storing packages.

### Patch Changes

- Updated dependencies [91c4b5954]
  - @pnpm/store-controller-types@8.0.0-alpha.0
  - @pnpm/store-connection-manager@0.3.0-alpha.0

## 1.0.10

### Patch Changes

- 907c63a48: Update `@pnpm/store-path`.
- Updated dependencies [907c63a48]
- Updated dependencies [907c63a48]
- Updated dependencies [907c63a48]
- Updated dependencies [907c63a48]
  - @pnpm/store-connection-manager@0.2.31
  - @pnpm/get-context@1.2.1
  - @pnpm/cli-utils@0.4.4
