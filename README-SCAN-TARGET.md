# Scan target (temporary)

Temporary scan target for an authorized security review of Cregis AnyChain.

- Source: https://github.com/0xcregis/anychain @ `63aa543`
- Contents: `crates/anychain-kms` + its path dependency `crates/anychain-core` only
- Workspace `Cargo.toml` trimmed to these two members; all dependency pins unchanged
- License: MIT/Apache-2.0 (see LICENSE, same as upstream)

This repo exists only so the scanner can run on one crate within the free-model
request budget. It will be deleted after the scan.
