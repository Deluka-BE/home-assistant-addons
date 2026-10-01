# Changelog

## 0.2.2

- Use the public MCP endpoint `/mcp` as the Auth0 API audience.
- Keep OAuth protected-resource metadata, Auth0 audience and JWT resource validation aligned on the same `/mcp` URL.
- Verified OAuth discovery and unauthenticated MCP challenge behavior.
- Verified linux/amd64 and linux/arm64 images.
- Existing Home Assistant configuration fields remain unchanged.

## 0.2.1

- Stable Home Assistant update version for the verified OAuth discovery fix.
- Exact retag of the previously verified multi-arch OAuth-fix image.
- No configuration changes; existing Hevy, Auth0, CalDAV, Codex and Spotify options remain valid.

# Changelog

## 0.2.0-test-oauth-mcp-938d7f2-1

- Fix MCP OAuth protected-resource discovery for the public `/mcp` endpoint.
- Preserve the existing Auth0 API audience while advertising the correct MCP resource URL.
- Verified private multi-arch GHCR image for linux/amd64 and linux/arm64.
- Hevy, iCloud Calendar / CalDAV, Codex bridge and Spotify remain included.

## 0.2.0-test-spotify-d342904

- First repository-managed Home Assistant release.
- Hevy support.
- iCloud Calendar / CalDAV support.
- Codex bridge support.
- Spotify provider support.
