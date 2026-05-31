# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

**RE:GE** (Recursive Engine: Generative Entity) is a symbolic operating system for myth, identity, ritual, and recursive systems. It consists of:

1. **Specification Documentation** (`docs/`) - Mythic-academic framework expressed through interconnected Markdown
2. **Python Implementation** (`rege/`) - Fully functional executable system

## Repository Structure

```
recursive-engine--generative-entity/
├── rege/                    # Python implementation
│   ├── core/                # Constants, models, exceptions
│   ├── parser/              # Invocation syntax parser
│   ├── routing/             # Soul Patchbay queue system
│   ├── organs/              # 10 organ handlers
│   ├── protocols/           # FUSE01, recovery, enforcement
│   ├── persistence/         # JSON archive system
│   └── tests/               # Test suite
├── docs/                    # Specification documentation
│   ├── core/                # Core system docs (4NTHOLOGY, constants, linkmap)
│   ├── organs/              # Organ specifications (01-22)
│   ├── protocols/           # Protocol specifications (FUSE01, recovery)
│   ├── interfaces/          # OS interface docs (ritual access, bridges)
│   ├── academic-wing/       # Academic expansion chambers (08-12)
│   └── archive/             # Historical/symbolic fragments
├── README.md                # Project overview and usage
├── CLAUDE.md                # This file
├── CONTRIBUTING.md          # Contribution guidelines
├── LICENSE                  # MIT License
└── pyproject.toml           # Package configuration
```

## Documentation Architecture

### Core System Files (`docs/core/`)
- `RE-GE_4NTHOLOGY_INIT.v1.0.md` - Main comprehensive system documentation
- `RE-GE_RECURSIVE_SYSTEM_RENDER_LINKMAP.md` - Inter-organ routing and connections
- `RE-GE_CONSTANTS_CHARGE_THRESHOLDS.md` - 5-tier charge system

### Organizational Bodies (`docs/organs/`)
22 thematically-named modules functioning like organs of a symbolic body:
- **01 Heart of Canon** - Core mythology and canon events
- **02 Mirror Cabinet** - Reflection and interpretation
- **03 Mythic Senate** - Law governance
- **04 Archive Order** - Storage and retrieval
- **05 Ritual Court** - Ceremonial logic and contradiction resolution
- **06 Code Forge** - Symbol-to-code translation (Python, Max/MSP, JSON)
- **07 Bloom Engine** - Generative growth and mutation
- **08 Soul Patchbay** - Modular routing hub (all modules connect through here)
- **09 Echo Shell** - Recursion interface, whispered loops
- **10 Dream Council** - Collective processing and prophecy
- **11 Mask Engine** - Identity layers and persona assembly
- **12-22** - Commerce, Blockchain, Monetizer, Audience, Place, Time, Analog-Digital, Process-Product, Consumption, Stagecraft, Publishing

### Academic Wing (`docs/academic-wing/`)
- `RE-GE_ORG_BODY_00_ACADEMIA_WING_PROTOCOL.md` - Foundational academic layer
- `RE-GE_AAW_CORE_08_CANONIZATION_ENGINE.md` - How objects enter personal canon
- `RE-GE_AAW_CORE_09_INTERLOCUTOR_PROTOCOLS.md` - Dialogue with ghosts, masks, symbolic beings
- `RE-GE_AAW_CORE_10_GENEALOGY_ENGINE.md` - Symbolic lineage and influence mapping
- `RE-GE_AAW_CORE_11_FAILURE_STUDY_CHAMBER.md` - Ritual study of collapse and abandonment
- `RE-GE_AAW_CORE_12_MYTHICAL_CITATION_SYSTEM.md` - Recursive attribution and echo tracking

### Protocols (`docs/protocols/`)
- `RE-GE_PROTOCOL_FUSE01.md` - Fragment fusion protocol
- `RE-GE_PROTOCOL_SYSTEM_RECOVERY.md` - System recovery protocol
- `RE-GE_PROTOCOL_COLLABORATOR.md` - Collaboration protocol

### Interfaces (`docs/interfaces/`)
- `RE-GE_OS_INTERFACE_01_RITUAL_ACCESS_CONTROLLER.md` - Invocation syntax for calling organs
- `RE-GE_OS_INTERFACE_02_EXTERNAL_BRIDGES.md` - Obsidian, Git, Max/MSP integration

## Python Implementation

### Key Modules (`rege/`)

| Module | Purpose |
|--------|---------|
| `core/constants.py` | Charge tiers, priorities, depth limits |
| `core/models.py` | Fragment, Patch, Invocation data classes |
| `parser/invocation_parser.py` | Ritual syntax parser |
| `routing/patchbay.py` | Priority queue system |
| `organs/*.py` | 10 organ handlers |
| `protocols/fuse01.py` | Fusion protocol |
| `cli.py` | Command-line interface |

### CLI Commands

```bash
rege invoke '<ritual syntax>'    # Execute invocation
rege status                      # Show system status
rege repl                        # Interactive mode
rege fragments list|show|create  # Fragment management
rege checkpoint create|list      # Checkpointing
rege recover [mode]              # System recovery
```

## Key Concepts

### Invocation Syntax
Organs are called using ritual syntax:
```
::CALL_ORGAN [ORGAN_NAME]
::WITH [SYMBOL or INPUT]
::MODE [INTENTION_MODE]
::DEPTH [light | standard | full spiral]
::EXPECT [output_form]
```

### Charge System
| Tier | Range | Behavior |
|------|-------|----------|
| LATENT | 0-25 | Background, no processing |
| PROCESSING | 26-50 | Active consideration |
| ACTIVE | 51-70 | Full engagement |
| INTENSE | 71-85 | Canon candidate |
| CRITICAL | 86-100 | Immediate action |

### Tag System
Content tagged for tracking: `CANON+`, `ECHO+`, `ARCHIVE+`, `VOLATILE+`, `RITUAL+`, `MIRROR+`, `REMIX+`, `MASK+`, `FUSE+`

### LG4 Translation Modes
Symbol-to-code conversion patterns:
- `FUNC_MODE` - Lyrics become Python functions
- `CLASS_MODE` - Archetypes become classes
- `WAVE_MODE` - Emotions become waveforms/LFOs
- `TREE_MODE` - Sentences become flowcharts
- `SIM_MODE` - Myths become simulations

### Laws
79+ recursive laws govern the system (e.g., LAW_01: Recursive Primacy, LAW_06: Symbol-to-Code Equivalence)

## Development

### Running Tests
```bash
pytest                      # Run all tests
pytest --cov=rege           # With coverage
pytest rege/tests/test_parser.py -v  # Specific file
```

### Working with Documentation
- Maintain the ritual/mythic tone and formatting conventions
- Use the established tag system when adding content
- Respect the inter-organ routing logic (Soul Patchbay as hub)
- Follow the 7-module AAW study flow: INPUT_RITUAL → RAA_ACADEMIC_LOOP → EMI_MYTH_INTERPRETATION → AA10_REFERENCIAL_CROSSMAPPING → SELF_AS_MIRROR → CODE_EXPORT_SCT → RECURSION_ENGINE_ARCHIVE

## File Naming Convention
`RE-GE_[TYPE]_[NUMBER]_[NAME].md`
- TYPE: ORG_BODY, OS_INTERFACE, AAW_CORE, PROTOCOL
- Stylized with `4` replacing `A` in certain contexts (ET4L, R!4L)

<!-- ORGANVM:AUTO:START -->
## System Context (auto-generated — do not edit)

**Organ:** ORGAN-I (Theory) | **Tier:** flagship | **Status:** GRADUATED
**Org:** `organvm-i-theoria` | **Repo:** `recursive-engine--generative-entity`

### Edges
- **Produces** → `unspecified`: theory

### Siblings in Theory
`organon-noumenon--ontogenetic-morphe`, `auto-revision-epistemic-engine`, `narratological-algorithmic-lenses`, `call-function--ontological`, `sema-metra--alchemica-mundi`, `cognitive-archaelogy-tribunal`, `a-recursive-root`, `radix-recursiva-solve-coagula-redi`, `.github`, `nexus--babel-alexandria`, `4-ivi374-F0Rivi4`, `cog-init-1-0-`, `linguistic-atomization-framework`, `my-knowledge-base`, `scalable-lore-expert` ... and 10 more

### Governance
- Foundational theory layer. No upstream dependencies.

*Last synced: 2026-05-23T00:26:28Z*

## Active Handoff Protocol

If `.conductor/active-handoff.md` exists, **READ IT FIRST** before doing any work.
It contains constraints, locked files, conventions, and completed work from the
originating agent. You MUST honor all constraints listed there.

If the handoff says "CROSS-VERIFICATION REQUIRED", your self-assessment will
NOT be trusted. A different agent will verify your output against these constraints.

## Session Review Protocol

At the end of each session that produces or modifies files:
1. Run `organvm session review --latest` to get a session summary
2. Check for unimplemented plans: `organvm session plans --project .`
3. Export significant sessions: `organvm session export <id> --slug <slug>`
4. Run `organvm prompts distill --dry-run` to detect uncovered operational patterns

Transcripts are on-demand (never committed):
- `organvm session transcript <id>` — conversation summary
- `organvm session transcript <id> --unabridged` — full audit trail
- `organvm session prompts <id>` — human prompts only


## System Library

Plans: 269 indexed | Chains: 5 available | SOPs: 8 active
Discover: `organvm plans search <query>` | `organvm chains list` | `organvm sop lifecycle`
Library: `/Users/4jp/Code/organvm/praxis-perpetua/library`


## Active Directives

| Scope | Phase | Name | Description |
|-------|-------|------|-------------|
| system | any | atomic-clock | The Atomic Clock |
| system | any | execution-sequence | Execution Sequence |
| system | any | multi-agent-dispatch | Multi-Agent Dispatch |
| system | any | session-handoff-avalanche | Session Handoff Avalanche |
| system | any | system-loops | System Loops |
| system | any | prompting-standards | Prompting Standards |
| system | any | background-task-resilience | background-task-resilience |
| system | any | context-window-conservation | context-window-conservation |
| system | any | session-self-critique | session-self-critique |
| system | any | the-descent-protocol | the-descent-protocol |
| system | any | the-membrane-protocol | the-membrane-protocol |
| system | any | theory-to-concrete-gate | theory-to-concrete-gate |
| system | any | triangulation-protocol | triangulation-protocol |
| unknown | any | gpt-to-os | SOP_GPT_TO_OS.md |
| unknown | any | index | SOP_INDEX.md |
| unknown | any | obsidian-sync | SOP_OBSIDIAN_SYNC.md |

Linked skills: SOP-TRIADIC-REVIEW-PROTOCOL, cicd-resilience-and-recovery, continuous-learning-agent, evaluation-to-growth, genesis-dna, multi-agent-workforce-planner, promotion-and-state-transitions, quality-gate-baseline-calibration, repo-onboarding-and-habitat-creation, session-self-critique, structural-integrity-audit, the-membrane-protocol, triple-reference


**Prompting (Anthropic)**: context 200K tokens, format: XML tags, thinking: extended thinking (budget_tokens)


## Atomization Pipeline

Run `organvm atoms pipeline --write && organvm atoms fanout --write` to generate task queue.


## System Density (auto-generated)

AMMOI: 25% | Edges: 0 | Tensions: 0 | Clusters: 0 | Adv: 27 | Events(24h): 37975
Structure: 8 organs / 148 repos / 1654 components (depth 17) | Inference: 0% | Organs: META-ORGANVM:63%, ORGAN-I:53%, ORGAN-II:48%, ORGAN-III:54% +5 more
Last pulse: 2026-05-23T00:26:28 | Δ24h: n/a | Δ7d: n/a


## Dialect Identity (Trivium)

**Dialect:** FORMAL_LOGIC | **Classical Parallel:** Logic | **Translation Role:** The Grammar — defines well-formedness in any dialect

Strongest translations: III (formal), IV (formal), META (formal)

Scan: `organvm trivium scan I <OTHER>` | Matrix: `organvm trivium matrix` | Synthesize: `organvm trivium synthesize`


## Logos Documentation Layer

**Status:** ACTIVE | **Symmetry:** 0.5 (DREAM)

Nature demands a documentation counterpart. This formation maintains its narrative record in `docs/logos/`.

### The Tetradic Counterpart
- **[Telos (Idealized Form)](../docs/logos/telos.md)** — The dream and theoretical grounding.
- **[Pragma (Concrete State)](../docs/logos/pragma.md)** — The honest account of what exists.
- **[Praxis (Remediation Plan)](../docs/logos/praxis.md)** — The attack vectors for evolution.
- **[Receptio (Reception)](../docs/logos/receptio.md)** — The account of the constructed polis.

### Alchemical I/O
- **[Source & Transmutation](../docs/logos/alchemical-io.md)** — Narrative of inputs, process, and returns.

- **[Public Essay](https://organvm-v-logos.github.io/public-process/)** — System-wide narrative entry.

*Compliance: Record exists without implementation.*

<!-- ORGANVM:AUTO:END -->












## ⚡ Conductor OS Integration
This repository is a managed component of the ORGANVM meta-workspace.
- **Orchestration:** Use `conductor patch` for system status and work queue.
- **Lifecycle:** Follow the `FRAME -> SHAPE -> BUILD -> PROVE` workflow.
- **Governance:** Promotions are managed via `conductor wip promote`.
- **Intelligence:** Conductor MCP tools are available for routing and mission synthesis.