# Hiero SDK Python Contributions

**Organization:** LF Decentralized Trust / Hiero  
**Repository:** [hiero-ledger/hiero-sdk-python](https://github.com/hiero-ledger/hiero-sdk-python)

## Merged Pull Requests

1. [#2640 — feat(tck): implement createEthereumTransaction](https://github.com/hiero-ledger/hiero-sdk-python/pull/2640) — Implemented the `createEthereumTransaction` JSON-RPC TCK method, parameter parsing, transaction mapping, validation, and unit tests.
2. [#2500 — feat(tck): implement createFile JSON-RPC method](https://github.com/hiero-ledger/hiero-sdk-python/pull/2500) — Added `createFile` TCK JSON-RPC support, request/response models, transaction mapping, and tests.
3. [#2483 — add clear_custom_fee_limits()](https://github.com/hiero-ledger/hiero-sdk-python/pull/2483) — Added fluent custom-fee-limit clearing with freeze protection and tests.
4. [#2477 — Rename memo field to topicMemo](https://github.com/hiero-ledger/hiero-sdk-python/pull/2477) — Fixed topic/transaction memo name collisions and added serialization regression tests.
5. [#2452 — Replace print statements with logger](https://github.com/hiero-ledger/hiero-sdk-python/pull/2452) — Replaced print/traceback debugging with structured logging across query and network modules and added regression tests.
6. [#2450 — implement dissociateToken JSON-RPC method](https://github.com/hiero-ledger/hiero-sdk-python/pull/2450) — Added TCK parameters, response model, handler, and tests.
7. [#2433 — add token grant/revoke KYC handlers](https://github.com/hiero-ledger/hiero-sdk-python/pull/2433) — Added `grantTokenKyc` and `revokeTokenKyc` TCK JSON-RPC handlers and supporting models/tests.

## Engineering Themes

Python · SDK development · JSON-RPC · protobuf · TCK · pytest · API behavior · structured logging · regression testing