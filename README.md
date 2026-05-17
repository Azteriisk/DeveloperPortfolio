# Alec Brandt (Azteriisk) - Project History

This document is a single writeup of my project history across local repositories, unpublished prototypes, Unreal projects, SNHU coursework, and public GitHub work.

- Some entries are prototypes, research studies, or design documents rather than polished commercial releases. I label those honestly because they still show meaningful engineering ability.

## Snapshot

I am currently a student at SNHU, but most of my growth has come from building outside class across a wide range of technologies: Rust, C++, C, TypeScript, Go, Python, Unreal Engine, Vulkan, JUCE, Slint, Tauri, Next.js, Clerk, SpacetimeDB, Bevy, raylib, Slang, Strudel, and Matrix. Across these projects, a few patterns show up repeatedly:

- I gravitate toward local-first and offline-capable tools. (mostly because servers cost money and I dont want to take up my computer's resources)
- I like systems that are realtime, interactive, or performance-sensitive.
- I move between product design, implementation, debugging, and documentation instead of staying in one narrow lane.
- I am comfortable learning new stacks by building something concrete with them.

## What This History Demonstrates

- Systems depth: compiler experiments, graphics programming, DSP/audio work, realtime networking, native desktop applications.
- Product thinking: design docs, replacement-system planning, UX-focused prototypes, offline workflows, admin tooling.
- Breadth with intent: not random repo collecting, but repeated attempts to understand how software works under the hood.
- Academic alignment: software design, testing, systems analysis, security, and technical communication all show up in the work.

## Timeline

### 2024 - Foundations and deliberate exploration

- May 2024 - [Rust-HTTP-Server-Base](https://github.com/Azteriisk/Rust-HTTP-Server-Base)
  A practice HTTP server in Rust. This was an early systems project that shows low-level curiosity and a willingness to learn backend fundamentals from the protocol level up. Main learning: ownership, request handling, and why "simple server" code becomes serious quickly once correctness matters.

- June 2024 - [Blazor-.NET-Test](https://github.com/Azteriisk/Blazor-.NET-Test)
  A short .NET and Blazor web experiment. Main learning: component-based frontend patterns in the Microsoft stack and how server/web tooling differs from the JavaScript ecosystem I later used more heavily.

- August 2024 - [HeliumCompiler](https://github.com/Azteriisk/HeliumCompiler)
  A C++ compiler-learning project focused on accepting ASCII `.he` files and compiling toward assembly. Main learning: parsing, code generation, and how compilers force precision in language design and error handling.

- August 2024 - [VeryFunctionalCalculator](https://github.com/Azteriisk/VeryFunctionalCalculator)
  A hackathon-style JavaScript project. Main learning: shipping a playful idea quickly under time pressure while still organizing UI logic and making the project presentable.

- August 2024 - [graplet](https://github.com/Azteriisk/graplet)
  A TypeScript block-programming concept centered on building apps and programs with interactive blocks. Main learning: visual programming interfaces, state management, and designing software for users who think structurally rather than syntactically.

- August 2024 - [django_tests](https://github.com/Azteriisk/django_tests)
  A Django exploration focused on static site generation and integrated admin capabilities. Main learning: batteries-included backend frameworks, data admin workflows, and how much scaffolding a mature framework can remove.

- August 2024 - [VoxelGO](https://github.com/Azteriisk/VoxelGO) and [Voxall](https://github.com/Azteriisk/Voxall)
  Early voxel-engine work in Go and C++. These are important because they show a recurring graphics/rendering interest that later continued into Vulkan, browser 3D, simulation, and custom engines. Main learning: spatial data structures, rendering pipelines, and the tradeoff between ambitious engine ideas and implementation complexity.

- September 2024 - [azterisk-net](https://github.com/Azteriisk/azterisk-net)
  An early TypeScript web project. Main learning: modern frontend project structure and deployment-minded web development.

- October 2024 - [OneLastMission](https://github.com/Azteriisk/OneLastMission)
  An Unreal Engine 5 project. Main learning: engine workflow, asset organization, and the realities of working inside a large commercial engine rather than a minimal custom framework.

### 2025 - Moving from experiments into stronger technical identity

- January 2025 - [MeshNet](https://github.com/Azteriisk/MeshNet)
  A browser-based 3D engine idea aimed at using the GPU while staying performant at scale. Main learning: browser graphics constraints and how web delivery changes engine architecture decisions.

- February 2025 - [SDLOdin](https://github.com/Azteriisk/SDLOdin)
  A small game-oriented project built while learning Odin and SDL2. Main learning: low-level game loop structure, language exploration, and working without the abstraction layers common in web stacks.

- July 2025 - `ChadaTechClocks` (SNHU CS 210)
  A C++ console application that displays synchronized 12-hour and 24-hour clocks with interactive time controls. Main learning: class design, encapsulation, formatted output, and input validation. This is straightforward coursework, but it is a good marker of disciplined C++ fundamentals and clear code organization.

- July 2025 to February 2026 - [World_Sim](https://github.com/Azteriisk/World_Sim)
  A Rust and Bevy Earth-system simulator aimed at geological, climate, and crop modeling. It includes multi-layer Earth systems, plate tectonics, procedural terrain, climate modeling, biome classification, and 3D visualization. Main learning: scientific-model decomposition, simulation architecture, realtime visualization, and how to organize a large technical ambition into layered subsystems.

- September 2025 - [free-bot](https://github.com/Azteriisk/free-bot)
  A Discord bot in Python that announces temporarily free paid games on Epic and Steam, with region-awareness, admin controls, polling, and SQLite persistence. Main learning: external API edge cases, Discord bot ergonomics, lightweight persistence, and deployment-minded scripting.

- September 2025 - [CRM-Term](https://github.com/Azteriisk/CRM-Term)
  A terminal-based CRM written in Go. Main learning: business-software thinking in a constrained UI, speed-first design, and cross-platform CLI/TUI style workflows.

- September 2025 - [Netflix-Visualizer](https://github.com/Azteriisk/Netflix-Visualizer)
  A data visualization project where particles represent viewer clusters around Netflix titles using public Top 10 data. Main learning: turning datasets into narrative visual interfaces and balancing technical implementation with visual storytelling.

- October 2025 - [Vulkan_Tests](https://github.com/Azteriisk/Vulkan_Tests)
  A heavily commented Vulkan 1.3 mesh viewer and learning playground using GLFW, Assimp, ImGui, shaders, and cross-platform build scripts. Main learning: modern graphics APIs, build system discipline, shader/toolchain integration, and the value of writing code that can teach the next reader.

- November 2025 - [terminal-emulator](https://github.com/Azteriisk/terminal-emulator)
  A web terminal built with Next.js that simulates commands, themes, and a filesystem entirely in the browser. Main learning: interaction design, command parsing, UX polish inside a constrained interface, and how to turn a portfolio concept into a memorable product surface.

- November 2025 - [quickswitch-ui](https://github.com/Azteriisk/quickswitch-ui)
  A Next.js showcase with multiple radically different UI templates driven by shared content. Main learning: separation of content from presentation, design-system flexibility, and building frontend architecture that can support experimentation without duplicating data.

- November 2025 - `CodeVox` (local, unpublished)
  A Go-based offline voice-driven coding assistant using Vosk and PortAudio, with command mode, dictation mode, and low-latency local ASR. Main learning: speech tooling, desktop-oriented audio plumbing, offline UX constraints, and the engineering details needed to keep realtime voice systems practical on commodity hardware.

- December 2025 - [PseudoIDE](https://github.com/Azteriisk/PseudoIDE)
  A Tauri desktop IDE that turns pseudocode into code using local LLM inference, with React, TypeScript, Monaco, Rust, and side-by-side execution workflow. Main learning: AI-assisted tooling, desktop app architecture, bridging frontend and native code, and building privacy-focused local developer tools rather than thin wrappers around cloud APIs.

- December 2025 - `Reclamation` (local design document)
  A full game design document for a large multiplayer settlement/economy/combat game with procedural worlds, politics, crafting, and long-form progression. Main learning: systems design, economy balancing, progression loops, and communicating a complex technical/game vision in a structured design artifact.

- December 2025 - [epstein_files](https://github.com/Azteriisk/epstein_files)
  A satirical asymmetric deduction game concept. Main learning: rules design, framing mechanics for social interaction, and writing mechanics clearly enough that others could implement or playtest them.

### 2026 - Integration, realtime products, audio, and engine work

- January 2026 - [MoreDynamic](https://github.com/Azteriisk/MoreDynamic)
  A replacement-system specification for legacy Microsoft Dynamics order entry, targeting Android and Windows with strong offline support. This is systems analysis and product planning rather than finished software. Main learning: translating messy business requirements into a structured architecture, thinking about sync, quote state, audit logs, product catalogs, and admin workflows.

- January to April 2026 - [SpectralSubtractor](https://github.com/Azteriisk/SpectralSubtractor)
  A JUCE-based VST3 plugin for realtime spectral subtraction noise reduction, built as both an audio tool and a DSP study. Main learning: FFT-based DSP, overlap-add reconstruction, thread-safe audio/UI architecture, realtime visualization, and plugin lifecycle engineering. This is one of the clearest examples of me going deep technically instead of just assembling frameworks.

- January to March 2026 - Unreal Engine prototype series
  Local projects include `UEIntroProject`, `TopDownTemplate`, `TopDownRPG`, `2D-Template`, `Iso2D`, `CozyRosie`, `MetaHumanTest`, and `PlatformingTest`. Main learning: rapid prototyping in UE5, template modification, top-down and platforming controls, isometric presentation, level prototyping, asset integration, and broad engine familiarity. The value here is not one finished title but repeated contact with real engine workflows.

- February 2026 - [gamechat](https://github.com/Azteriisk/gamechat)
  A native desktop chat application in Rust using Slint and Matrix, positioned as a lower-bloat Discord alternative. Main learning: native UI architecture, protocol-backed messaging, session persistence, role/channel administration, and how to recreate familiar social UX without defaulting to Electron.

- February to March 2026 - [makerspace](https://github.com/Azteriisk/makerspace)
  A Next.js App Router site with Clerk auth and a SpacetimeDB-backed member dashboard for storefront, education, repairs, community, and admin flows. Main learning: full-stack product integration, auth flows, realtime data, generated bindings, admin access design, and building a system that feels like a product rather than a demo page.

- February 2026 - `pxlengine` (local)
  A Rust pixel-engine sandbox using `pixels`, `wgpu`, `winit`, `egui`, `rayon`, and `rodio`, with world state, entities, GUI/editor modes, and audio hooks. Main learning: custom engine structure, low-resolution rendering pipelines, tool overlays, and how to compose simulation/editor ideas in a native Rust graphics application.

- February 2026 - `slasher` (local)
  A Rust engine experiment using `winit`, `wgpu`, `rapier3d`, `hecs`, `glam`, and `nalgebra`. Main learning: ECS-oriented structure, rendering + physics coordination, and the bootstrapping work required before "gameplay" even exists in engine code.

- March 2026 - [spacetimedb-shared-canvas](https://github.com/Azteriisk/spacetimedb-shared-canvas)
  A realtime collaborative canvas built with React 19, TanStack Router, Clerk, and SpacetimeDB, including admin-only snapshot and wipe controls. Main learning: realtime collaboration, auth-gated ownership rules, multiplayer state synchronization, and turning backend subscriptions into an intuitive shared UI.

- March 2026 - [steam-launch-optimizer](https://github.com/Azteriisk/steam-launch-optimizer)
  A Python scripting project for Linux game launch optimization. Main learning: automation for real user pain points, scripting repeatable fixes, and documenting operational workflows that many people do manually.

- April 2026 - [stage](https://github.com/Azteriisk/stage)
  A browser-based live-coding environment linking a Strudel music runtime to a GLSL shader runtime through a reactive binding layer. Main learning: cross-domain runtime synchronization, reactive systems design, and high-performance browser rendering for audiovisual synthesis.

- April 2026 - [sslb](https://github.com/Azteriisk/sslb)
  A turing-complete shader transpiler with a high-precision interactive 3D runner. Main learning: language transpilation, compiler theory applied to shaders, and designing flexible runners for modern high-density visual engines.

- April 2026 - [raylib-sim-tests](https://github.com/Azteriisk/raylib-sim-tests)
  A C and raylib cellular automata sandbox with data-driven block definitions, runtime tuning, custom input bindings, and specialized growth/merge behavior. Main learning: simulation architecture in plain C, data-driven behavior registration, rendering discipline without heavy frameworks, and keeping a graphics/simulation codebase modular.

- April 2026 - [RCWExpertHauling](https://github.com/Azteriisk/RCWExpertHauling)
  A premium commercial website for a local debris hauling service. Built on Next.js with unified Royal Blue and dark mode themes, it features an infinite-scrolling service gallery and local SEO location mapping. Main learning: optimizing client-facing pre-rendering architectures, mobile-first design system scaling, and production deployment pipeline engineering.

- May 2026 - [CareerReport (resume-builder)](https://github.com/Azteriisk/CareerReport)
  A full-stack professional networking platform and high-fidelity resume builder. Features a horizontal scrollWidth-calculated pagination engine, an invisible structured ATS & AI metadata injection layer (with double-layer plain text and JSON-LD), custom Next.js self-hosted font bundling, and a Google Gemini API zero-cold-start PDF parser, backed by Clerk authenticated PostgreSQL Supabase Row-Level Security and a collaborative social suite (posts, comments, quote reposts, follower mechanics, and real-time private direct messages). Main learning: resolving complex web-to-PDF print styling boundaries using layout-affecting zoom and absolute scaling mechanics, mapping cross-platform authenticated JWT tokens to granular PostgreSQL RLS rules, and maintaining real-time reactive data consistency across high-density interactive views.

## Academic Work at SNHU

I am currently studying at SNHU, and that work matters because it reinforces the engineering habits visible in my independent projects:

- software design and systems analysis
- data structures and algorithmic thinking
- testing and quality awareness
- security and secure software practices
- written technical communication

Visible local and GitHub evidence includes `ChadaTechClocks` and multiple portfolio repositories tied to CS coursework such as CS-210, CS-230, CS-250, CS-255, CS-300, CS-305, and CS-320. Even when those repos are private or not fully mirrored locally, they reinforce that my project history is not purely hobby-driven; it is also being sharpened in a formal academic setting.

## Open Source and External Code Exploration

Not everything in my folders is original product work, but those repositories are still part of my growth:

- `Valdi` - exploration of a native-performance cross-platform UI framework and its CLI/install workflow.
- `demand` - inspection of a Rust prompt library.
- `Odin`, `vcpkg`, `dia`, and related mirrors/dependencies - used as learning references, tools, or upstream code, not presented as my own authored projects.

This matters to employers because reading, debugging, and navigating other peoples' code is a separate skill from building greenfield projects. I have done both.

## Technology Breadth

Languages I have used in meaningful projects:
- Rust
- C++
- C
- TypeScript
- Go
- Python
- C# / .NET
- Lua
- Odin
- Slang
- GLSL

Frameworks, engines, and tools that recur across the portfolio:
- Next.js, React, Vite, Tailwind
- Supabase (PostgreSQL + RLS)
- Google Gemini API
- Bun
- Tauri
- Slint
- JUCE
- Vulkan, GLFW, Assimp, ImGui
- Bevy
- raylib
- wgpu / pixels / winit
- Unreal Engine 5
- Strudel
- Clerk
- SpacetimeDB
- Matrix SDK
- SQLite

## Overall Assessment

The strongest pattern in my history is not just "I know many languages." It is that I repeatedly pick technically demanding problems and build enough of them to understand the real constraints: offline-first behavior, performance, synchronization, visualization, DSP correctness, engine architecture, and admin/product workflows.

For academics, this portfolio shows curiosity, self-direction, and a willingness to learn difficult material by implementing it. For employers, it shows range, initiative, and evidence that I can move between product-oriented software, native systems work, realtime interaction, and formal coursework without needing to stay inside one stack.

If I were describing my profile so far in one sentence, I would say:

I am a student developer with strong self-directed systems curiosity, growing product judgment, and a portfolio that already spans frontend, backend, native desktop, graphics, audio, simulation, and game tooling.
