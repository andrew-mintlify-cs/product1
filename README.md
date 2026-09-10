# Product1

Test monorepo for validating Mintlify multi-repo documentation setups.

This repository simulates a product monorepo where documentation lives alongside source code, mirroring a customer setup where a `documentation/` directory in the product monorepo is added as a source in a Mintlify multi-repository deployment.

Documentation content is located in:

- `documentation/` — the Mintlify source directory. Contains its own `docs.json` plus `data-extraction-engine/`, `data-load-controller/`, `internal/`, and `java-sdk/` sections. In the Mintlify dashboard, add this repo as a source with **docs.json is in a subdirectory** set to `/documentation`.
- `product1-feature-documentation/` — feature-specific documentation
- `product1-python-sdk/docs/` — Python SDK documentation

All other directories are placeholder modules representing typical monorepo components.
