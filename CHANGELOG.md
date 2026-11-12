# Changelog

## 0.2.3

### Patch Changes

- 166fa29: Return the registered component API from the `/test` helper, making
  it available to tests that use `defineTestApp`.

## 0.2.2

- Updates types for `ctx` arguments for better compatibility with Convex v1.41+

## 0.2.1

- Updates the schema for twilio's response changes, and makes the parsing more
  robust.

## 0.2.0

- Adds /test and /\_generated/component.js entrypoints
- Drops commonjs support
- Improves source mapping for generated files
- Changes to a statically generated component API
