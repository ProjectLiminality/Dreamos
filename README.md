# DreamOS

The grand unification of all meaningful dimensions of the digital into one coherent, tightly integrated system. A complete refactoring of the digital into something ergonomic to the human mind and organic to the social sphere.

**DreamOS = InterBrain minus everything that's not the InterBrain.** Going from InterBrain to DreamOS is purification, not addition. InterBrain in a folder on macOS → same thing but the folder IS your user directory → that's DreamOS. Every external dependency removed is a step closer. The vault becomes the user directory becomes the operating system.

**AURYN is the heart of DreamOS.** DreamOS is the horizon — the complete vision of sovereign computing. AURYN sits at the center. The knowledge garden lives in between. The Poincaré disc: AURYN at the origin, DreamOS as the boundary at infinity, relevance realization continuously moving things from horizon to center. You never arrive at DreamOS — you grow toward it from AURYN outward.

**SaaS is over.** Every subscription collapses into one cost: inference. Cinema 4D → DreamTalk. Zoom → own WebRTC. YouTube → own media player. Spotify → own library. The InterBrain/DreamOS stack vertically owns the entire surface area of digital life. The only remaining external cost is the electricity to think — LLM inference — and even that decentralizes as local models improve.

## The Fundamental Property

**Every DreamNode is a place you can meet people.**

Not "some apps have multiplayer." Not "here's a special collaborative document." Every unit of the system - by default - is a place where you can invite friends. This is true on desktop and mobile equally — one codebase, Tauri targets both. A smartphone running DreamOS is not a lesser version. It is the same system.

```
macOS window buttons:    [🔴 Close] [🟡 Minimize] [🟢 Maximize]
DreamOS window buttons:  [🔴 Close] [🟡 Minimize] [🟢 Maximize] [👥 Invite]
```

## The Ontological Inversion

| Traditional Digital | DreamOS |
|---------------------|---------|
| File system | Dream system |
| File explorer | Dream explorer |
| Browsing a website | Cloning a repository - you acquire, not visit |
| Browse alone, some sites collaborate | Every place is multiplayer by default |
| Apps isolated, some have lobbies | Every app is a potential lobby |
| Video calls in meta-space | Video calls *inside* meaningful contexts |
| "Here's a group, let me explain" | The place IS the introduction |

**The context carries the semantic meaning of why you're together.** You don't introduce people and then explain - you invite them into a story you've woven.

## The Ownership Inversion: You Cannot Visit Without Owning

This may be the deepest novelty of DreamOS.

### Current Web Architecture

```
┌─────────────────────────────────────────┐
│           Corporate Server              │
│    (Miro, Google, Figma, etc.)          │
│                                         │
│    The "place" lives HERE               │
│    You are a GUEST                      │
└───────────┬─────────────┬───────────────┘
            │             │
      ┌─────▼─────┐ ┌─────▼─────┐
      │  Alice    │ │   Bob     │
      │ (client)  │ │ (client)  │
      │  guest    │ │  guest    │
      └───────────┘ └───────────┘
```

### DreamOS Architecture

```
┌─────────────────┐         ┌─────────────────┐
│     Alice       │         │      Bob        │
│                 │         │                 │
│  ┌───────────┐  │  sync   │  ┌───────────┐  │
│  │ DreamNode │◄─┼─────────┼─►│ DreamNode │  │
│  │ (owned)   │  │  Yjs    │  │ (owned)   │  │
│  └───────────┘  │ actions │  └───────────┘  │
│                 │         │                 │
│  Full source    │         │  Full source    │
│  Full history   │         │  Full history   │
│  Full agency    │         │  Full agency    │
└─────────────────┘         └─────────────────┘
```

**You cannot visit a place without owning it.**

The moment you join, you clone the full DreamNode:
- Complete source (not just rendered output)
- Full git history (every change ever made)
- Sovereign ownership (it's YOUR copy now)

What syncs is tiny: cursor positions, CRDT operations, presence. The place itself lives in each person's machine. You're not streaming a world from a server - you're both in your own worlds, with a tiny synchronization layer making them coherent.

### The Metaphysical Coherence

This mirrors how reality actually works:

**Incoherent model** (current web):
- One entity "hosts" reality
- Others are guests in someone else's dream
- The world exists "out there" on a server

**Coherent model** (DreamOS):
- Each participant contains the full context
- The place exists in every dreamer's mind
- Meeting = synchronizing sovereign realities

The holographic principle applied to the digital: every part contains the whole. No "master copy" - all copies are real. DreamOS makes the digital match the noetic.

## Places and Topology

A DreamNode is a place. Places connect:
- **Horizontally**: Liminal web (sociocratic, peer relationships)
- **Vertically**: Holarchy (submodule containment)

You can:
1. Visit a place alone (monologos - async appreciation)
2. Meet others there (dialogos - synchronous presence)
3. Travel together through the holarchy
4. Introduce friends to each other *in* a meaningful context

## The Evolution Path

Each step is exciting standalone. Together, unprecedented.

### Stage 1: Canvas Dreamweaving (NOW)
- Shared canvas for connecting DreamTalks
- Single-player, async collaboration via git
- Running in the InterBrain Tauri app (extracted from the original Obsidian plugin)

### Stage 2: Multiplayer Canvas (NEXT)
- Real-time CRDT sync (Yjs)
- Shared cursors, voice chat
- Meet in a DreamNode, dreamweave together

### Stage 3: Iframe Embedding
- Turn any website into a DreamNode
- Browse the existing web from within DreamOS
- Meet friends and browse together

### Stage 4: Interactive DreamSongs (DreamTalk as UI)
- DreamSong evolves from linear canvas to interactive 3D UI
- DreamTalk renderer (wgpu + Vello) replaces browser-based rendering entirely — including the webview itself
- The DreamTalk Rust/wgpu runtime renders the entire UI natively. No browser engine needed for native apps. This is the final step of DreamOS sovereignty — the last external dependency (the webview) dissolves
- 3D is default, 2D is the edge case (orthographic camera, z=0 plane)
- Tiling window management = layout containers (same code for OS-level and in-app layout)
- Voice-driven AI builds interfaces
- The back of a DreamNode becomes a full application
- A "video" is just a constrained linear traversal of an interactive scene — pause and fly around at any time

### Stage 5: Universal Multiplayer
- Every DreamNode is a potential lobby
- The social button is everywhere

## The Iframe Bridge

We don't need to rebuild the web - we can *contain* it:

```
┌─────────────────────────────────────────┐
│           DreamNode: DPI Archive         │
│  ┌───────────────────────────────────┐  │
│  │   <iframe src="dpi-archive.org">  │  │
│  │      Existing website rendered    │  │
│  └───────────────────────────────────┘  │
│  [Alice 🖱️]  [Bob 🖱️]  [AURYN 🤖]       │
│  Two cursors, voice chat, AI copilot    │
└─────────────────────────────────────────┘
```

Existing websites become DreamNodes. Multiplayer comes from the DreamOS layer, not the site itself.

## Architecture Vision

A minimal system where your screen becomes a scrying mirror and speech-to-dream is the primary interface.

### Unix Philosophy Revival

DreamOS returns to the elegance of Unix and Plan 9:

- **Everything is a file** - All state lives in the filesystem, GUI is a view into it
- **CLI as truth layer** - Every meaningful action is a CLI command
- **GUI as thin membrane** - Captures gestures, invokes CLI, renders output
- **Composable via pipes** - DreamNodes chain together like Unix tools

DreamTalk's Rust runtime (wgpu + Vello) handles all rendering — native GPU, no browser engine required. Gestures translate to CLI invocations. Actual work happens in Unix tools. The browser is one deployment target (via WASM), not the foundation.

### Bridge Injection: Transport-Agnostic Custom UIs

A DreamNode's `index.html` runs in multiple contexts — a Tauri webview, a local browser, a phone over Tailscale — each with a different communication transport. The custom UI author should never think about this.

The solution: the host environment injects the bridge. When the Tauri app serves `index.html` in a webview, it injects a `<script>` that provides a `bridge` global using Tauri's IPC. When the Python server serves the same file to an external browser, it injects a `bridge` global using WebSocket. The custom UI just calls `bridge.send()` and `bridge.onMessage()` — same API, different transport underneath.

This means:
- Custom UI authors write against one interface
- No `bridge.js` file ships with the DreamNode — the bridge appears automatically, like a browser API
- The bridge implementation can evolve without touching any custom UI
- The same `index.html` works in every context without modification

The protocol (message types like `ai-inference-stream-request`, `cli-exec`, `dreamnode-catalog-request`) is the contract. The transport is an implementation detail hidden by injection.

### Plan 9 Extension: Runtime State as Files

Plan 9 took Unix's "everything is a file" further - exposing memory, process state, and network connections through the file system. DreamOS adopts this via FUSE.

Each DreamNode exposes runtime state in a `.state/` directory:

```
DreamNode/
├── README.md           # What it is
├── cli/                # What it does
├── .state/             # What it's doing right now (gitignored)
│   ├── errors          # Runtime errors
│   ├── status          # Current state
│   └── [app-specific]  # Whatever state matters
```

**Agent debuggability**: An AI debugging a broken app runs `cat /App/.state/errors` - no special protocols, just files.

### CLI as Universal API (MCP Obsolescence)

MCP exists to make APIs self-describing for AI. But CLI already is that:
- `ffmpeg --help` describes itself
- `man ffmpeg` goes deeper
- The README describes intent

The pattern: clone a DreamNode, read its README, invoke its CLI. Solved once, kept forever. No subscriptions, no API limits, no "service discontinued."

### Primary Interface: Speech-to-Dream

Voice your will, AI agents execute. Keyboard and mouse become secondary - used only when inspecting or making precise adjustments.

### Headless by Default

Most interactions happen through AURYN orchestrating AI agents. You kick things off by speaking ideas; the system enriches plans across different DreamNode contexts, which you can then fire off when coherent.

## User Directory as Digital Twin

The user directory becomes a monorepo containing your digital interior. Everything meaningful lives there, populated by DreamNodes. The folder with your name IS you, digitally.

### Light and Shadow: The Intentionality Boundary

Not everything belongs in the user directory. The principle: **does a human or AI agent ever intentionally invoke this by name?**

**The Light** (user directory as DreamNodes):
- File spirits: `cat`, `ls`, `cp`, `mv`, `rm`
- Search spirits: `grep`, `find`, `which`
- Network spirits: `curl`, `wget`, `ssh`
- Media spirits: `ffmpeg`, `imagemagick`
- Version spirit: `git`

These are beings you summon by name. They deserve READMEs, symbols, source code.

**The Shadow** (kernel, drivers, plumbing):
- Memory management, process scheduling
- GPU drivers, WiFi chipset code
- Filesystem internals, dynamic linker

Infrastructure that serves without being addressed. Hidden like your autonomic nervous system.

### Unix Tools as DreamNodes

```
~/cat/
├── README.md     # "Cat reads files and outputs their contents."
├── symbol.svg    # Visual representation
├── .udd          # UUID, relationships
├── src/          # Source code
└── bin/          # Compiled binary
```

Now `cat` isn't a mystery - it's a digital spirit in your collection. Grandma's recipe and `curl` exist as peers in the same ocean of DreamNodes. Some are processes (verbs), some are substances (nouns), some are people (dreamers). All sovereign beings in your digital world.

## Cloud Without Centralization

iCloud vs local distinction dissolves:
- **Git history**: Accidental deletion recoverable
- **GitTorrent F2F transport**: Friend-to-friend git synchronization — your trusted peers mirror your repos, no infrastructure needed. The liminal web IS the transport layer
- **No corporate dependency**: Your friends hold your data, not Apple/Google

You couldn't ever lose important things because they're held in your network.

## Online/Offline Melding

Everything local by default - no internet needed. But signal to friends you're "here" in a DreamNode context, and they can hop in. Not binary (private vs public with strangers) but gradual (private → friends can join).

Everyone interacts with their version; meaningful changes become git commits via LLM intelligence. Transient actions (mouse movements) forgotten, meaningful actions (text edits) persist.

## The Social Graph Underneath

All of this rests on the liminal web:
- You don't meet strangers
- You deepen relationships with people you know
- Friends introduce you to their friends
- Trust propagates through the network

When you "browse together," it's with your actual social graph, in contexts that matter.

## Platform Strategy

### Dual Distribution

1. **Application Ecosystem** - Runs on any existing OS (macOS, Windows, Linux)
2. **Standalone Linux** - Runs directly on hardware via Arch Linux

The standalone version is the pure expression - no legacy OS cruft.

### Why Arch Linux

Arch provides minimal foundation: kernel, systemd, networking, audio, GPU drivers. Nothing more.

DreamOS simplifies dramatically:
- Single UI runtime (DreamTalk renderer: winit + wgpu + Vello — no browser engine, no Tauri, no webview)
- Collapsed choices (no DE/WM selection — DreamTalk IS the compositor)
- Minimal surface — the stack is: kernel → Wayland → DreamTalk renderer

The DreamTalk renderer talks directly to the GPU via Metal/Vulkan. A native window, not a wrapped browser. This means:
- ~20-50MB RAM for the entire UI (vs 200-500MB per Electron/webview window)
- Zero CPU for idle UI (GPU renders, CPU sleeps)
- Boot to usable: 3-5 seconds
- A 2014 laptop with integrated graphics runs DreamOS smoothly — the same hardware that's "unusable" under Windows 11 + Chrome

### Agentic Installation

AI can detect hardware, make partitioning decisions, execute installation, troubleshoot errors. Voice-guided setup on any hardware.

**Installation phases**: Hardware scan on Windows → User configuration → Custom ISO generation → Guided installation via AI.

**The Dual Boot Demonstration**: Windows 11 boot: 30-90 seconds. DreamOS/Arch boot: 3-5 seconds. Users experience what their hardware is actually capable of.

### Global Hardware Liberation

The standalone Arch distribution unlocks hundreds of millions of functional laptops rendered "unusable" by OS bloat. A 2012 laptop with network connectivity accesses the same AI capabilities as a 2024 MacBook.

**The Family Server Model**: One revived laptop serves an entire household. Data stays in the family, not extracted by corporations.

**Viral Distribution**: DreamOS spreads peer-to-peer via USB stick. Every activated machine can create more installation media. Once in circulation, unstoppable.

**The Agentic Leapfrog**: The ascending world doesn't need incremental hardware upgrades - it can leapfrog directly into the agentic age on hardware the descending world discarded.

## Technical Foundation

### DreamNode Structure: The Single-File Holon

```
DreamNode/
├── README.md             # What it is (for humans and AI)
├── DreamNode.py          # THE file: symbol + logic + CLI + UI — all in one
├── .udd                  # UUID, type, relationships
├── assets/               # Binary blobs (models, textures, audio)
└── submodules/           # Other DreamNodes this one composes
    ├── DreamTalk/        # Core library
    └── OtherHolon/       # Sovereign dependency
```

**One file per holon.** The `.py` file defines the DreamTalk symbol (visual), the functionality (logic), and the CLI interface (for AI agents and UI routing). GUI for humans, CLI for machines — everything routes through the CLI.

Complexity is managed by **depth, not breadth**: if something grows complex enough to be its own thing, extract it into a submodule (new DreamNode repo). Never split horizontally into sibling files — split vertically into the holarchy.

Interaction model: **click symbol → CLI invocation → output display**. Drag file onto symbol → `python DreamNode.py process <file>`. The symbol IS the app.

### Bootstrapping Pattern

DreamOS installation from a DreamNode clones itself into a monorepo it creates - fully self-referential. Every component is a DreamNode, including DreamOS itself.

### Transport Layer: Git + BitTorrent

Large files distribute via decentralized Git LFS:
- Git tracks pointers (sha256 oid + size)
- BitTorrent delivers bytes
- DHT for discovery
- Streaming support for video playback during transfer
- Organic swarm growth - each clone becomes a seeder

### CRDT-Enabled Multiplayer

CRDTs (Conflict-free Replicated Data Types) allow:
- No central authority needed
- Operations merge deterministically
- Each copy is authoritative
- Eventual consistency guaranteed

Yjs is battle-tested at scale. For small groups (the liminal web's trust network), performance considerations are negligible.

### Dynamic Tool Inheritance

DreamNodes pulled in via semantic search contribute their CLI tools to the active context. Importing a DreamNode as submodule adds its tools to your PATH.

## The Profound Implication

Every app in your operating system becomes a potential meeting place.

Not "let me screen share while we're on a call."
Not "let me send you a link to this collaborative tool."

Just: "I'm in this place. Want to join me?"

The digital finally becomes *spatial* the way physical reality is. This is what the metaverse was supposed to be - but emerging from meaningful contexts (your actual ideas, your actual relationships) rather than empty 3D spaces waiting to be filled.

## Related

- **InterBrain** - The Tauri app — DreamOS running inside an existing OS
- **AURYN** - The heart — agentic layer, template, CLI tools, knowledge gardening
- **Collective-Dreamweaving** - The dialogos layer (multiplayer)
- **DreamTalk** - The rendering engine that eventually replaces the webview entirely
- **Software Gardening** - The development philosophy
