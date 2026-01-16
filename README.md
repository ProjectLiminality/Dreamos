# DreamOS

The complete reimagining of the operating system paradigm - where your screen becomes a scrying mirror and speech-to-dream is the primary interface.

## Core Transformation

| Traditional OS | DreamOS |
|----------------|---------|
| File system | Dream system |
| File explorer | Dream explorer |
| App launcher | Dream launcher |
| Applications | DreamNodes with unified knowledge + tools |

## Architecture Vision

A minimal Linux distribution running one primary system: the dream space. No bureaucratic tools, no traditional text editors needed. UIs become optional, generated on demand by AI.

### Primary Interface: Speech-to-Dream

Voice your will, and AI agents execute. The keyboard and mouse become secondary - used only when inspecting or making precise adjustments to generated outputs.

### Headless by Default

Most interactions happen through AURYN orchestrating AI agents. You kick things off by speaking ideas; the system enriches plans across different DreamNode contexts, which you can then fire off when coherent.

## Technical Foundation

### Bootstrapping Pattern

DreamOS installation from a DreamNode clones itself into a monorepo it creates - fully self-referential. Every component is a DreamNode, including DreamOS itself.

### Deduplication via Git LFS

Large files (videos, assets) deduplicate across submodules through Git LFS backend. Same file in different submodule versions points to same LFS object. Aggressive thresholds keep the system lightweight.

### Dynamic Tool Inheritance

DreamNodes pulled in via semantic search can dynamically contribute their MCP tools to the active context. File path based MCP loading with consistent `mcp.json` at root convention.

## Security Considerations

Leaving the entire traditional OS paradigm opens opportunity for ground-up security design. Minimal attack surface - only what's needed for dream space operation.

## Related

- **InterBrain** - The Obsidian plugin foundation
- **AURYN** - The MCP meta-interface
- **Software Gardening** - The development philosophy
