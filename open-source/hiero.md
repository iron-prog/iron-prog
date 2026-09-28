# Hiero SDK Python Contributions

**Organization:** LF Decentralized Trust / Hiero  
**Repository:** [hiero-ledger/hiero-sdk-python](https://github.com/hiero-ledger/hiero-sdk-python)

## Summary

Contributed SDK functionality, JSON-RPC TCK handlers, test coverage, logging improvements, and bug fixes to the Hiero Python SDK.

## Contribution Areas

### JSON-RPC / TCK
Implemented and tested handlers including:
- `createEthereumTransaction`
- `createFile`
- `dissociateToken`
- token grant/revoke KYC handlers

Work included generated protobuf integration, parameter handling, unit tests, and TCK validation.

### SDK functionality
Implemented `clear_custom_fee_limits()` for transaction fee-limit handling.

### Bug fixing
Fixed a Topic memo attribute collision involving `TopicCreateTransaction` and `TopicUpdateTransaction`.

### Logging modernization
Replaced direct `print` / traceback-style debugging with structured logging across 14 files.

### Testing and verification
Used pytest and the TCK suite to validate behavior, including focused unit tests and broader test runs for handler changes.

## Engineering Themes

Python · SDK development · JSON-RPC · protobuf · TCK · pytest · API behavior · structured logging · regression testing