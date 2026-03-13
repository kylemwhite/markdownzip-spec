# Fixture Archives

Prebuilt `.mdz` archives generated from the source directories in [`../`](../README.md).

Files:

- `minimal.mdz`
- `with-manifest.mdz`
- `invalid-missing-index.mdz`
- `invalid-bad-entrypoint.mdz`
- `line-endings-crlf.mdz`

Machine-readable behavior fixtures:

- `entrypoint-cases.json`
- `path-validation-cases.json`
- `create-filter-cases.json`

These JSON fixtures are intended to be consumed by multiple implementations
(for example, C# and TypeScript) so both can assert the same behavior from a
shared source of truth.
