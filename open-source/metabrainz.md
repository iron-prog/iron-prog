# MetaBrainz Contributions

**Organization:** MetaBrainz  
**Repositories:** [MusicBrainz Picard](https://github.com/metabrainz/picard) · MCP MusicBrainz

## MusicBrainz Picard

Contributed to the core desktop application, with work including high-risk filesystem and state-management behavior.

### File and state handling
Worked on:
- inode-based file-change detection;
- configuration-migration hooks;
- save-state regression prevention.

These changes required understanding how Picard detects external file changes and persists application state.

## MCP MusicBrainz

Contributed tools and transport functionality for an MCP server exposing MusicBrainz capabilities to AI agents.

### Tools
Implemented functionality for:
- ISRC / ISWC translation;
- MusicBrainz entity details;
- offset-based pagination designed for LLM/tool consumers.

### Transport
Contributed an SSE transport entry point for MCP clients.

## Engineering Themes

Python · desktop applications · filesystem behavior · state management · MCP · AI tooling · API integration