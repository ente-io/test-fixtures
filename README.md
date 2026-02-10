# test-fixtures

Shared test fixtures for Ente apps and libraries.

## Layout

- `media/`: Images, videos, and metadata fixtures used by media parsers/classifiers.
- Future domains can add top-level folders (for example `auth/`, `sync/`, `ml/`) as needed.

## Versioning

Fixtures are grouped by dataset and version, for example:

- `media/motion-photos/v1/`

Add new datasets as `v2`, `v3`, etc. when expected outputs or fixture semantics change.
