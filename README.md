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

## User Directory as Digital Twin

The user directory becomes a monorepo containing your digital interior. Everything meaningful lives there, populated by DreamNodes. The folder with your name IS you, digitally.

macOS scatters this simplicity: Applications folder, iCloud sync, hidden Library with cache files. DreamOS reclaims elegant unity - if an app produces cache, it lives in that DreamNode's repo, not scattered system directories. Dream Explorer shows only your monorepo; system internals remain accessible via terminal but hidden from GUI.

## Cloud Without Centralization

iCloud vs local distinction dissolves. DreamNodes have cloud-like properties via:
- **Git history**: Accidental deletion recoverable
- **Radicle remotes**: Decentralized P2P mirroring through liminal web
- **No corporate dependency**: Your friends hold your data, not Apple/Google

You couldn't ever lose important things because they're held in your network.

## Online/Offline Melding

Everything local by default - no internet needed. But signal to friends you're "here" in a DreamNode context, and they can hop in. Not binary (private vs public with strangers) but gradual (private → friends can join).

**Holochain SYNC** or similar: decentralized real-time collaboration. Everyone interacts with their version; meaningful changes become git commits via LLM intelligence. Transient actions (mouse movements) forgotten, meaningful actions (text edits) persist.

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
