# MetaBrainz Contributions

**Organization:** MetaBrainz  
**Repositories:** [MusicBrainz Picard](https://github.com/metabrainz/picard) · [MCP MusicBrainz](https://github.com/zas/mcp-musicbrainz)

## MusicBrainz Picard — Merged Pull Requests

1. [#3058 — Add musicbrainz_composerid tag](https://github.com/metabrainz/picard/pull/3058) — Added composer MusicBrainz Artist IDs as a dedicated metadata tag.
2. [#3047 — Fix incorrect comment in FileIdentity hash test](https://github.com/metabrainz/picard/pull/3047) — Corrected inaccurate test documentation.
3. [#3044 — Fix macOS background-only app](https://github.com/metabrainz/picard/pull/3044) — Fixed the PyInstaller macOS console setting so the generated app behaves as a normal foreground application.
4. [#3010 — Test file deleted after capture](https://github.com/metabrainz/picard/pull/3010) — Added save-pipeline regression coverage for a file deleted after loading.
5. [#3009 — Add regression test for file deleted after identity capture](https://github.com/metabrainz/picard/pull/3009) — Added FileIdentity coverage for external deletion.
6. [#3005 — Regression test for replaced file with same size](https://github.com/metabrainz/picard/pull/3005) — Added coverage for same-size replacement with different content.
7. [#2963 — Detect external file change](https://github.com/metabrainz/picard/pull/2963) — Added lightweight inode/size/mtime/content-hash based detection between load and save.
8. [#2954 — Docs set error docstring](https://github.com/metabrainz/picard/pull/2954) — Improved documentation around error behavior.
9. [#2933 — Improve error messages for file access errors](https://github.com/metabrainz/picard/pull/2933) — Improved diagnostics for filesystem access failures.

## MCP MusicBrainz — Merged Pull Requests

1. [#18 — Add SSE transport entry point using native FastMCP](https://github.com/zas/mcp-musicbrainz/pull/18) — Added a native FastMCP SSE transport entry point.
2. [#7 — Add offset parameter to search tools](https://github.com/zas/mcp-musicbrainz/pull/7) — Added pagination offsets for LLM/tool consumers.
3. [#6 — Add ISRC/ISWC translation tools](https://github.com/zas/mcp-musicbrainz/pull/6) — Added industry-standard ISRC and ISWC lookup/translation tools.
4. [#2 — Add event, instrument, place, and series detail tools](https://github.com/zas/mcp-musicbrainz/pull/2) — Added entity-detail tools for additional MusicBrainz resource types.
5. [#1 — Add release-group cover-art tool and handle 404s](https://github.com/zas/mcp-musicbrainz/pull/1) — Added release-group cover-art retrieval with explicit Cover Art Archive 404 handling.

## Engineering Themes

Python · desktop applications · filesystem behavior · state management · MCP · FastMCP · MusicBrainz APIs · pagination · AI tooling