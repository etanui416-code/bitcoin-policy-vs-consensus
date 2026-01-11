
# Bitcoin Policy vs Consensus

This repository documents my study of the distinction between Bitcoin
policy rules and consensus rules.

Understanding this separation is critical for safe Bitcoin development,
as policy rules may change while consensus rules must remain stable.

## Topics Covered
- Definition of policy vs consensus rules
- Standardness rules and mempool behavior
- Miner policy vs network consensus
- Examples where policy differs from consensus
- Security implications of policy changes

## Why This Matters
Mistaking policy for consensus can lead to unsafe assumptions,
network splits, or rejected transactions. This repository exists
to build a clear mental model before contributing code.

## Methodology
- Review Bitcoin Core documentation and source code
- Read historical PRs and discussions
- Document edge cases and real-world scenarios

## Status
Work in progress. Notes added incrementally.
