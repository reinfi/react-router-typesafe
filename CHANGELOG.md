# react-router-typesafe

## 1.5.0

### Minor Changes

- a001404: typesafeBrowserRouter now infers correct paths for relative paths

### Patch Changes

- a001404: Fixed an issue where mixed paths with children and without would lead to flaky inference of paths

## 1.4.4

### Patch Changes

- 1093a48: `typesafeBrowserRouter`: cache union of all paths in router scope

## 1.4.3

### Patch Changes

- 1c5a838: Pathless routes with children now correctly infer their path

## 1.4.2

### Patch Changes

- 41af0d5: Improve compiler performance for the `href` function returned by `typesafeBrowserRouter` by lazily calculating route params

## 1.4.1

### Patch Changes

- 8917a9d: `typesafeBrowserRouter`: no longer requires `pathParams` to be passed as an empty object when route does not have dynamic segments

## 1.4.0

### Minor Changes

- ce9bf9d: Added new utility `typesafeBrowserRouter`

## 1.3.4

### Patch Changes

- `useActionData` now ignores Response objects as expected

## 1.3.3

### Patch Changes

- a85b1a7: Add link to github repo to npm

## 1.3.2

### Patch Changes

- Fixed re-export of useRouteLoaderData from mistakenly exporting useLoaderData to the right module

## 1.3.1

### Patch Changes

- Export `useRouteLoaderData`

## 1.3.0

### Minor Changes

- 8355264: Patch <Await> component

## 1.2.0

### Minor Changes

- Add `useLoaderData` hook types
- Migrate from pnpm to bun

## 1.1.0

### Minor Changes

- Add `makeLoader`, `makeAction` utilities
  Re-exported `ActionFunction, `LoaderFunction`and`redirect` for commodity

## 1.0.1

### Patch Changes

- 9706126: Fixed files exposed with package.json

## 1.0.0

### Major Changes

- Initial release
