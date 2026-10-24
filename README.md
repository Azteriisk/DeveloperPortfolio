# Alec Brandt (Azteriisk) - Project History

This document is a single writeup of my project history across local repositories, unpublished prototypes, Unreal projects, SNHU coursework, and public GitHub work.

- Some entries are prototypes, research studies, or design documents rather than polished commercial releases. I label those honestly because they still show meaningful engineering ability.

## Snapshot

I am currently a student at SNHU, but most of my growth has come from building outside class across a wide range of technologies: Rust, C++, C, TypeScript, Go, Python, Java, Unreal Engine, Vulkan, OpenGL, JUCE, Slint, Tauri, Next.js, Clerk, SpacetimeDB, Bevy, raylib, Slang, Strudel, Matrix, Android SDK, and Linux desktop system engineering (Hyprland, Wayland, Quickshell, PipeWire). Across these projects, a few patterns show up repeatedly:

- I gravitate toward local-first and offline-capable tools. (mostly because servers cost money and I don't want to take up my computer's resources)
- I like systems that are realtime, interactive, or performance-sensitive.
- I move between product design, implementation, debugging, and documentation instead of staying in one narrow lane.
- I am comfortable learning new stacks by building something concrete with them.

## What This History Demonstrates

- **Systems depth:** compiler experiments, Vulkan & OpenGL graphics programming, DSP/audio work, hardware accelerometer telemetry, realtime networking, and native desktop/shell applications.
- **Product thinking:** design docs, replacement-system planning, UX-focused prototypes, offline workflows, administrative tooling, and live commercial SaaS platforms.
- **Breadth with intent:** not random repo collecting, but repeated attempts to understand how software works under the hood from the kernel and hardware up to the user interface.
- **Academic alignment:** software design, testing, systems analysis, security, algorithms, and technical communication all show up in the work.

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
  A Next.js showcase with multiple radically different UI templates driven by shared content, paired with an interactive WebGL particle system. Main learning: separation of content from presentation, design-system flexibility, and building frontend architecture that can support experimentation without duplicating data.

- November 2025 - `CodeVox` (local, unpublished)  
  A Go-based offline voice-driven coding assistant using Vosk and PortAudio, with command mode, dictation mode, and low-latency local ASR. Main learning: speech tooling, desktop-oriented audio plumbing, offline UX constraints, and the engineering details needed to keep realtime voice systems practical on commodity hardware.

- December 2025 - [PseudoIDE](https://github.com/Azteriisk/PseudoIDE)  
  A Tauri desktop IDE that turns pseudocode into code using local LLM inference, with React, TypeScript, Monaco, Rust, and side-by-side execution workflow. Main learning: AI-assisted tooling, desktop app architecture, bridging frontend and native code, and building privacy-focused local developer tools rather than thin wrappers around cloud APIs.

- December 2025 - `Reclamation` (local design document)  
  A full game design document for a large multiplayer settlement/economy/combat game with procedural worlds, politics, crafting, and long-form progression. Main learning: systems design, economy balancing, progression loops, and communicating a complex technical/game vision in a structured design artifact.

- December 2025 - [epstein_files](https://github.com/Azteriisk/epstein_files)  
  A satirical asymmetric deduction game concept. Main learning: rules design, framing mechanics for social interaction, and writing mechanics clearly enough that others could implement or playtest them.

### 2026 - Integration, realtime products, audio, systems, and ecosystem scale

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

- May to October 2026 - [CareerReport](https://github.com/Azteriisk/CareerReport)  
  A full-stack professional networking platform and high-fidelity resume builder. Features a horizontal scrollWidth-calculated pagination engine, an invisible structured ATS & AI metadata injection layer (with double-layer plain text and JSON-LD), custom Next.js self-hosted font bundling, full fluid drag-and-drop reordering with accessible touch/keyboard controls, and Google Gemini 2.5 Flash AI generation with zero-cold-start fallback to Gemini 2.5 Flash Lite. Supported by Clerk authentication, PostgreSQL Supabase Row-Level Security, and a complete collaborative social suite (posts, likes, quote reposts, follower mechanics, and real-time private direct messaging). Main learning: resolving complex web-to-PDF print styling boundaries using layout-affecting zoom and absolute scaling mechanics, scaling database schema migrations with cascading triggers and RLS policies, bridging fluid drag-and-drop animation with real-time PDF generation, and maintaining real-time reactive data consistency across high-density interactive views.

- June 2026 - [PatentFlow](https://github.com/Azteriisk/PatentFlow)  
  An intelligence and data-mining platform that queries and parses publicly available US Patent and Trademark Office (USPTO) filings to create actionable technology landscapes, competitive IP tracking, and inventor analytics. Main learning: navigating and indexing large, heterogeneous government datasets, optimizing complex keyword queries against unstructured patent descriptions, and presenting dense legal/technical filings as clean, high-value visual summaries.

- July 2026 - [SalesFlow](https://github.com/Azteriisk/SalesFlow)  
  A gamified, offline-first sales mapping and prospecting Progressive Web Application (PWA). Designed for field territory reps to discover local leads, organize daily stop routes, cache client interactions locally without continuous mobile data, and track real-time activity metrics. Main learning: offline-first PWA architectures, IndexedDB state caching with background synchronization, geospatial map visualization in bandwidth-constrained environments, and balancing gamification incentives with fast mobile fieldwork ergonomics.

- August 2026 - [UnknownFouriers](https://github.com/Azteriisk/UnknownFouriers)  
  A real-time Web Audio Fourier Transform ridgeline visualizer inspired by Joy Division's iconic *Unknown Pleasures* pulsar artwork. Features 3D pseudo-terrain perspective projection, continuous frequency slicing via Web Audio `AnalyserNode`, customizable multi-stop color gradients, integrated QWERTY/MIDI synth input, YouTube audio streaming capture, and 100% client-side privacy. Main learning: real-time frequency-domain digital signal processing (FFT), high-frame-rate HTML5 canvas rendering optimization, multi-source audio routing (microphone, audio stream, and synthetic oscillators), and converting mathematical DSP telemetry into aesthetic visual art.

- August 2026 - [cs2-radar-obs](https://github.com/Azteriisk/cs2-radar-obs)  
  An automated OBS Studio Python script that captures, crops, and projects an enlarged, real-time calibrated Counter-Strike 2 radar map onto a dedicated secondary monitor without adding perceptible frame latency or violating anti-cheat integrity. Main learning: OBS scripting API, video pipeline window capture hooks, game coordinate calibration, and building focused utility software that solves a specific competitive gaming workflow.

- August 2026 - [CS-SWE-Degree-Path](https://github.com/Azteriisk/CS-SWE-Degree-Path)  
  The comprehensive consolidation repository documenting my complete Southern New Hampshire University Computer Science and Software Engineering degree path. Consolidates codebases, design artifacts, and post-mortems across 10 specialized courses, including:
  - `CS-210`: Programming Languages & Algorithms (C++)
  - `CS-230`: Software Design & Architecture
  - `CS-250`: Software Development Lifecycle & Agile Methodologies
  - `CS-255`: System Design & Business Analysis
  - `CS-300`: Data Structures & Algorithms Analysis
  - `CS-305`: Software Security & Vulnerability Assessment
  - `CS-320`: Software Test Automation & Quality Assurance
  - `CS-330`: Computational Graphics & 3D Visualization (Modern OpenGL, custom GLSL shaders, camera transformations, lighting models)
  - `CS-350`: Emerging Systems Architectures & Technologies
  Main learning: formalizing academic rigor, writing exhaustive security and architectural audit documentation, demonstrating mastery across algorithms, 3D graphics, secure programming, and test-driven quality assurance.

- September 2026 - [dotfiles](https://github.com/Azteriisk/dotfiles) & Omarchy Linux Desktop Extensions  
  A modular multi-preset desktop environment and custom system extension suite for Omarchy Linux (built on Hyprland, Wayland, and Quickshell). Includes:
  - [omarchy-menu](https://github.com/Azteriisk/omarchy-menu): High-performance Quickshell desktop application launcher with games folder integration.
  - [omarchy-display-manager](https://github.com/Azteriisk/omarchy-display-manager): Interactive visual display manager with drag-and-drop monitor layout positioning and custom EDID scaling.
  - [omarchy-indicators](https://github.com/Azteriisk/omarchy-indicators): Reactive status bar widget tracking system telemetry, power, and stay-awake toggles.
  - [omarchy-idle-manager](https://github.com/Azteriisk/omarchy-idle-manager): Custom screensaver, lock-screen lifecycle controller, and user inactivity manager.
  - [omarchy-dlss](https://github.com/Azteriisk/omarchy-dlss): Zero-friction desktop manager for NVIDIA DLSS 5 Neural Rendering profiles on Wayland Linux.
  Main learning: Wayland compositor protocols, Hyprland IPC socket communication, QML/Quickshell declarative native UI development, Linux desktop shell ergonomics, and hardware-accelerated desktop rendering.

- October 2026 - [omarchy-wallpaper-engine](https://github.com/Azteriisk/omarchy-wallpaper-engine), [omarchy-games](https://github.com/Azteriisk/omarchy-games), [omarchy-boot-manager](https://github.com/Azteriisk/omarchy-boot-manager), and [omarchy-window-minimize](https://github.com/Azteriisk/omarchy-window-minimize)  
  Advanced native Linux desktop integration tools:
  - `omarchy-wallpaper-engine`: Native Steam Wallpaper Engine runner for Wayland/Hyprland supporting interactive Web, Video, and PipeWire reactive audio-visualizer scenes.
  - `omarchy-games`: Unified multi-platform game launcher consolidating Steam, Lutris, Wine, and RetroArch libraries into a seamless native interface.
  - `omarchy-boot-manager`: Linux-to-Windows dual-boot chainloader with automated `sbctl` Secure Boot key enrollment specifically for kernel anti-cheat compatibility (Valorant, FACEIT, EAC).
  - `omarchy-window-minimize`: Custom window minimization and scratchpad manager integrated directly into Hyprland window manager workflows.  
  Main learning: low-level Linux system management (systemd-boot, efibootmgr, TPM/Secure Boot keychains), PipeWire audio stream tapping, and seamless game runtime bridging across Linux wine/proton environments.

- October 2026 - [PhoneTossSurvival](https://github.com/Azteriisk/PhoneTossSurvival)  
  A high-stakes, telemetry-driven native Android game built in Java with the Android SDK. Directly reads hardware `Sensor.TYPE_ACCELEROMETER` data at maximum sampling rates to compute aerial free-fall duration, apogee, and impact force in $m/s^2$ and G-forces. Integrates Google Play Games Services V2 for global cryptographic leaderboards, local SQLite telemetry persistence, and a custom swipeable carousel UI. Main learning: native Android sensor lifecycle management, low-latency accelerometer filtering and gravity compensation, Google Play Services V2 authentication and leaderboard integration, and designing a game mechanic tightly bound to physical hardware telemetry.

- October 2026 - `WeightTracker` (local)  
  A focused Android health and bodyweight tracking application built with Java, Android SDK, and SQLite. Features automated daily SMS reminder integration via native SMSManager permissions, persistent historical record storage, and statistical change metrics. Main learning: native Android activity lifecycles, Android background broadcast receivers, SMS system permissions, and transactional SQLite database persistence.

- October 2026 - [CloneHeroCompanion](https://github.com/Azteriisk/CloneHeroCompanion)  
  A desktop companion and library management utility for Clone Hero and YARG rhythm games. Automates song chart discovery from Enchor and Chorus, parses `.chart` / `.mid` / `song.ini` metadata, converts Spotify playlists into matched song download bundles, and manages song directories without manual file unpacking. Main learning: third-party API aggregation, automated fuzzy string matching for artist/title reconciliation, batch archival extraction, and optimizing local disk indexing over rhythm game libraries containing tens of thousands of charts.

- October 2026 - [azterisk](https://github.com/Azteriisk/azterisk) & [azterisk-dashboard](https://github.com/Azteriisk/azterisk-dashboard)  
  The unified public portal and internal infrastructure observability suite for the Azterisk ecosystem (`azterisk.net`):
  - `azterisk`: Interactive celestial Constellation interface that renders all projects as interconnected, dynamically sized, non-overlapping nodes using responsive gravitational repulsion physics across any display size (mobile, laptop, 4K), accompanied by a unified command bar search modal and companion discovery assistant.
  - `azterisk-dashboard`: Engineering project radar that continuously monitors dependency staleness, CVE security advisories, plugin compatibility, deployment health, and uptime across all active live sites.  
  Main learning: designing physics-based procedural graph layouts that maintain legibility and aesthetic balance across extreme viewport variance without hardcoded positions, building real-time dashboard health monitoring, and creating a cohesive identity across dozens of independent software systems.

## Academic Work at SNHU

I am currently studying Computer Science at SNHU, and that work matters because it reinforces the engineering habits visible in my independent projects:

- software design and systems analysis
- data structures and algorithmic complexity
- testing, CI/CD automation, and quality assurance
- software security, vulnerability assessment, and defense-in-depth
- modern 3D graphics (OpenGL, vertex/fragment shaders, camera pipelines, illumination)
- written technical communication and architectural documentation

My complete academic portfolio is organized and documented in [CS-SWE-Degree-Path](https://github.com/Azteriisk/CS-SWE-Degree-Path), containing full project implementations across:
- **CS-210**: Programming Languages & Algorithms (C++) - `ChadaTechClocks`
- **CS-230**: Software Design & Architecture
- **CS-250**: Software Development Lifecycle & Agile Methodologies
- **CS-255**: System Design & Business Analysis
- **CS-300**: Data Structures & Algorithms Analysis
- **CS-305**: Software Security & Vulnerability Assessment
- **CS-320**: Software Test Automation & Quality Assurance
- **CS-330**: Computational Graphics & Visualization (Modern OpenGL, lighting, textured 3D models)
- **CS-350**: Emerging Systems Architectures & Technologies

This academic record reinforces that my project history is not purely hobby-driven; it is grounded in rigorous formal theory and computer science principles.

## Open Source and External Code Exploration

Not everything in my folders is original product work, but those repositories are still part of my growth:

- `Valdi` - exploration of a native-performance cross-platform UI framework and its CLI/install workflow.
- `demand` - inspection of a Rust prompt library.
- `Odin`, `vcpkg`, `dia`, and related mirrors/dependencies - used as learning references, tools, or upstream code, not presented as my own authored projects.

This matters to employers because reading, debugging, and navigating other people's code is a separate skill from building greenfield projects. I have done both.

## Technology Breadth

Languages I have used in meaningful projects:
- **Rust**
- **C++**
- **C**
- **TypeScript / JavaScript**
- **Go**
- **Python**
- **Java**
- **C# / .NET**
- **Lua**
- **Odin**
- **Slang / GLSL**
- **QML**

Frameworks, engines, and tools that recur across the portfolio:
- **Full-Stack & Web:** Next.js (App Router, Turbopack), React 19, TanStack Start / Router, Tailwind CSS, Vite, Bun, Node.js
- **Backend & Realtime:** Supabase (PostgreSQL, Row-Level Security, cascading triggers), SpacetimeDB (WebAssembly subscriptions), Clerk Authentication, SQLite
- **AI & Data:** Google Gemini 2.5 API (multimodal, structured output schemas, prompt engineering)
- **Mobile & Hardware:** Android SDK (Java, `SensorManager` accelerometer telemetry, Google Play Games Services V2, SMSManager)
- **Linux Desktop & Systems:** Hyprland / Wayland IPC, Quickshell, PipeWire audio routing, systemd-boot / sbctl Secure Boot
- **Desktop Native:** Tauri, Slint, JUCE (VST3 / Audio DSP), Matrix SDK
- **Graphics & Game Engines:** Vulkan 1.3, OpenGL (Programmable Pipeline, shaders, camera matrices), Bevy, raylib, wgpu / pixels / winit, Unreal Engine 5
- **Audio DSP:** Web Audio API (real-time FFT frequency slicing), Strudel, PortAudio, JUCE DSP
- **DevOps & Tooling:** Git, GitHub Actions CI/CD, Vercel CLI, OBS Studio Scripting

## Overall Assessment

The strongest pattern in my history is not just "I know many languages." It is that I repeatedly pick technically demanding problems and build enough of them to understand the real constraints: offline-first behavior, performance, synchronization, visualization, DSP correctness, engine architecture, native OS/hardware integration, and admin/product workflows.

For academics, this portfolio shows curiosity, self-direction, and a willingness to learn difficult material by implementing it. For employers, it shows range, initiative, and concrete evidence that I can move between product-oriented software, native systems work, realtime interaction, and formal coursework without needing to stay inside one stack.

If I were describing my profile so far in one sentence, I would say:

> I am a student developer with strong self-directed systems curiosity, growing product judgment, and a portfolio that spans full-stack web, native desktop, Linux system engineering, mobile hardware telemetry, graphics, audio DSP, simulation, and game tooling.
