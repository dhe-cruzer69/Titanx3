# ARIEX Control Contract

## Role
Browser automation and MCP server for structured, deterministic web interaction.

## Observed baseline
- Playwright-backed MCP server
- Accessibility-tree interaction
- Host/origin configuration controls
- Broad MCP client compatibility

## Advanced upgrade track
1. Add integration tests for allowed/blocked hosts and origins.
2. Add security profiles for trusted versus untrusted browsing.
3. Add deterministic browser fixtures and regression suites.
4. Add release provenance and dependency/SBOM checks.
5. Add execution telemetry without collecting sensitive page data.
6. Publish validated compatibility status to the fleet dashboard.

## Definition of done
Every release must pass browser regression, security configuration and package integrity checks.
