# @x12i/role-models usage example

Re-exports @x12i/agent-roles. Depend on @x12i/agent-roles for new work.

This consuming application demonstrates **read a historical role-model assignment through the re-exported api** using the published npm package, pinned to `1.0.0`.

## Run

Requires Node.js 24 or newer and npm. The example needs no service credentials.

```sh
npm install --ignore-scripts
npm start
```

## Example

[`src/index.mjs`](src/index.mjs) contains the complete example. Assertions check the demonstrated behavior and the program prints a small result.

## When to use the package

- Consume an existing role-model integration while planning migration to agent-roles.
- Resolve the canonical replacement package before starting a new integration.

## Links

- [npm package](https://www.npmjs.com/package/@x12i/role-models)

The `package.json` in this repository is private to prevent accidental publication of the example application under an npm package name.

## Validation scope

The definitions, outputs, callers, and source data are authored fixtures. Storage is in memory, and model assignment/resolution never invokes a provider. The function example executes only the source written in this repository; the package's Node VM mode is not a security boundary for untrusted code. The service authentication example inspects the demo/default hook and does not constitute a production authentication setup.
