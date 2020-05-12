# @pnpm/cafs

## 1.0.0-alpha.4

### Major Changes

- 471149e6: Change the format of the package index file. Move all the files info into a "files" property.

### Patch Changes

- @pnpm/fetcher-base@6.0.1-alpha.3

## 1.0.0-alpha.3

### Major Changes

- 9596774f2: Store the package index files in the CAFS to reduce directory nesting.
- 7852deea3: Instead of creating a separate subdir for executables in the content-addressable storage, use the directory where all the files are stored but suffix the executable files with `-exec`. Also suffix the package index files with `-index.json`.

## 1.0.0-alpha.2

### Minor Changes

- 42e6490d1: When a new package is being added to the store, its manifest is streamed in the memory. So instead of reading the manifest from the filesystem, we can parse the stream from the memory.

### Patch Changes

- c207d994f: Update rename-overwrite to v3.
- Updated dependencies [42e6490d1]
  - @pnpm/fetcher-base@7.0.0-alpha.2

## 1.0.0-alpha.1

### Minor Changes

- 4f62d0383: Executables are saved into a separate directory inside the content-addressable storage.

### Patch Changes

- Updated dependencies [4f62d0383]
  - @pnpm/fetcher-base@7.0.0-alpha.1

## 1.0.0-alpha.0

### Major Changes

- 91c4b5954: Project created.
- 91c4b5954: Using a content-addressable filesystem for storing packages.

### Patch Changes

- Updated dependencies [91c4b5954]
  - @pnpm/fetcher-base@7.0.0-alpha.0
