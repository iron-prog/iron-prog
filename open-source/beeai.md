# BeeAI Framework Contributions

**Organization:** BeeAI  
**Repository:** [i-am-bee/beeai-framework](https://github.com/i-am-bee/beeai-framework)

## Merged Pull Requests

### [#1429 — Make exclude_none configurable in MCPTool parameters](https://github.com/i-am-bee/beeai-framework/pull/1429)
Made MCP tool argument serialization configurable so callers can control whether `None` values are excluded when serializing Pydantic models.

- Added the `exclude_none` MCPTool option.
- Preserved the setting when cloning MCP tools.
- Updated model serialization to use the configurable option.
- Worked within the MCP tool execution path and validated the behavior through project checks.

### [#1409 — Improve Tool base class documentation and validation errors](https://github.com/i-am-bee/beeai-framework/pull/1409)
Improved the Tool base class documentation and validation/error behavior.

## Engineering Themes

Python · MCP · Pydantic · tool frameworks · validation · developer experience