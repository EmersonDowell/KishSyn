# KishSyn Core Rebase

Core theory behind this project: https://docs.google.com/document/d/1yFRS16gbqi4CIyVR5Y0OeUc9mNUDGx50/edit?usp=sharing&ouid=111998234953561188010&rtpof=true&sd=true

KishSyn Core is the clean living line after the older experimental KishAI/KishSyn archive. It is a deliberately small synthetic nervous-system substrate: one organism loop, one deterministic ecology, one synapse graph, one observatory, one evidence path, and governed milestone locks.

The project is R&D. It does not claim consciousness, AGI, or personhood. The purpose is to test whether adaptive organization can grow from lawful signal, focus, moment formation, body pressure, prediction, action, consequence, memory, replay, graph plasticity, and self-correction.

## Commercial Use, Sponsorship, and Contact

KishSyn / KishAI is an open research project exploring synthetic nervous-system architecture, grounded developmental learning, contextual affordances, memory economy, play-driven cognition, and safe staged embodiment.

The core code is intended to be released under **AGPL-3.0-or-later** so researchers, developers, students, and independent builders can study, run, modify, and contribute to the project while keeping derivative networked or distributed versions open under the same license.

If you are a company, lab, foundation, investor, researcher, educator, or developer interested in any of the following, please contact the project creator before building closed, hosted, commercial, or proprietary products around KishSyn:

- commercial licensing
- private deployment
- hosted or SaaS use
- research partnership
- sponsorship or grant support
- foundation or nonprofit support
- hardware / robotics collaboration
- academic collaboration
- investment or incubation
- paid development support
- media, demos, or interviews

KishSyn is not intended to be quietly absorbed into closed systems without discussion. The goal is to keep the core project open, scientifically honest, and contributor-friendly while allowing serious partners to support the work through sponsorship, funding, collaboration, or separate commercial agreements.

Project creator: **Emerson F. Dowell**  
Project: **KishSyn / KishAI**  
Contact: **[EmersonDowell@gmail.com]**  
Phone: (906) 361-3656

Support / Sponsorship: **[https://www.patreon.com/c/KishAI]**

If this project resonates with you and you want to help move synthetic organic intelligence research forward, contributions, issues, pull requests, feedback, funding, and serious collaboration inquiries are welcome.

## Current version

v040 starts and locks **M14: Interface Affordance Discovery** while preserving M7-M13. The repo now lets observed desktop/program UI elements become reusable interface signatures and proposal-only affordance contracts. Buttons, text fields, menus, consoles, files, webviews, and windows are learned as environment objects first, never as hidden automation handles. The future `.exe` path remains shell-independent: web, CLI, and desktop shells must all wrap the same organism loop and `stores/` brain state.

The active developmental chain is now:

```text
raw sensory signal
-> focus selection
-> MomentFrame
-> cross-modal binding
-> provisional circuit anatomy
-> intent persistence
-> counterfactual replay / proto-planning
-> emotional regulation field
-> bounded emotion bias contract
-> action
-> consequence
-> contextual affordance and object-file update
-> retention-pressure memory economy
-> safe intrinsic play
-> grounded language recall
-> desktop/OS read-only observation
-> interface affordance discovery
-> graph, memory, and state persistence
```

Milestone status:

- **M1 locked:** Focused Moment Substrate.
- **M2 locked:** Cross-Modal Binding and Intent Persistence.
- **M3 locked:** Counterfactual Replay and Proto-Planning.
- **M4 locked:** Sensory Adapter and Expression Surface.
- **M5 locked:** Neural Atlas Inspector and Synapse Introspection.
- **M6 locked:** Emotional Regulation Field.
- **M7 locked:** Emotion-Biased Attention and Expression.
- **M8 locked:** Contextual Affordance Cognition, Apple Across Worlds, and governed affordance bias contracts.
- **M9 locked:** Object-File Cortex, instance identity, shared object-kind anatomy, and transformation tracking.
- **M10 locked:** Retention Pressure and Memory Economy, compressed summaries, and no tick-specific memory-node leakage.
- **M11 locked:** Play and Intrinsic Experimentation, safe-enough proposals, and reusable play patterns.
- **M12 locked:** Grounded Language and Teaching, word-to-lived-anchor evidence, non-commanding language contracts, and no tick-specific language-node leakage.
- **M13 locked:** Desktop/OS Observation Substrate, read-only external surfaces, blocked write-like affordances, reusable OS/UI graph anatomy, state persistence, and desktop `.exe` portability doctrine.
- **M14 locked:** Interface Affordance Discovery, reusable UI element signatures, proposal-only affordance contracts, blocked write-like candidates, no `ui:t*` node leakage, and state persistence.

## What changed in v028

v028 adds `kishsyn_core/planning.py`, a bounded `CounterfactualReplayEngine`. The engine rehearses currently available action candidates before commitment. It scores options by graph prediction, confidence, projected body effect, distance cost, and risk. It may bias the chosen action only through an explicit report and only when the imagined option is meaningfully better.

The organism now writes reusable plan-template/prediction/outcome traces into the neural graph; tick-specific plan reports remain bounded audit history. The Observatory shows counterfactual options, imagined outcomes, risk, projected deltas, switches, alignment, reusable plan templates, and plan history inside the Focus / Action / Moment panel.

## Run gates

```powershell
python -m kishsyn_core.tools.dev_gates
```

Full pytest inventory in PowerShell:

```powershell
$env:PYTEST_DISABLE_PLUGIN_AUTOLOAD="1"; python -m pytest kishsyn_core/tests -q
```

## Run milestone locks

```powershell
python -m kishsyn_core.tools.run_milestone_m1_lock --out stores/_demo/milestone_m1_lock_report.json
python -m kishsyn_core.tools.run_milestone_m2_lock --out stores/_demo/milestone_m2_lock_report.json
python -m kishsyn_core.tools.run_milestone_m3_lock --out stores/_demo/milestone_m3_lock_report.json
python -m kishsyn_core.tools.run_milestone_m4_lock --out stores/_demo/milestone_m4_lock_report.json
python -m kishsyn_core.tools.run_milestone_m5_lock --out stores/_demo/milestone_m5_lock_report.json
python -m kishsyn_core.tools.run_milestone_m6_lock --out stores/_demo/milestone_m6_lock_report.json
python -m kishsyn_core.tools.run_milestone_m7_lock --out stores/_demo/milestone_m7_lock_report.json
python -m kishsyn_core.tools.run_milestone_m8_lock --out stores/_demo/milestone_m8_lock_report.json
python -m kishsyn_core.tools.run_milestone_m9_lock --out stores/_demo/milestone_m9_lock_report.json
python -m kishsyn_core.tools.run_milestone_m10_lock --out stores/_demo/milestone_m10_lock_report.json
python -m kishsyn_core.tools.run_milestone_m11_lock --out stores/_demo/milestone_m11_lock_report.json
python -m kishsyn_core.tools.run_milestone_m12_lock --out stores/_demo/milestone_m12_lock_report.json
python -m kishsyn_core.tools.run_milestone_m13_lock --out stores/_demo/milestone_m13_lock_report.json
python -m kishsyn_core.tools.run_milestone_m14_lock --out stores/_demo/milestone_m14_lock_report.json
```

## Run the benchmark and evidence reports

```powershell
python -m kishsyn_core.tools.run_benchmark_suite --steps 240 --seeds 337,171,23 --out stores/_demo/benchmark_suite_report.json
python -m kishsyn_core.tools.run_evidence_report --steps 240 --seed 337 --ablation-steps 48 --benchmark-seeds 337,171,23 --out stores/_demo/intelligence_evidence_report.json
```

The benchmark suite now checks delayed symbol-object matching, changed-object surprise, causal action controllability, route-memory transfer, target pursuit continuity, survival-symbol conflict arbitration, focused moment substrate, cross-modal binding, intent persistence, counterfactual replay proto-planning, emotional regulation, depletion-aware foraging, Apple Across Worlds contextual affordance, and symbol recall after save/load.

## Run the Observatory

```powershell
python -m kishsyn_core.observatory.server --port 8797 --hz 4
```

Open:

```text
http://127.0.0.1:8797/
```

The Observatory autostarts, loads `stores/_demo/persistent_brain_state.json` when it exists, autosaves every 120 ticks, and exposes world state, synaptic growth, focus/moment/action reasoning, counterfactual proto-planning, emotional regulation weather, text/tutor surfaces, benchmark/evidence reports, and report history.

## Run the headless organism

```powershell
python -m kishsyn_core.tools.run_core_world --steps 300 --seed 337 --out stores/_demo/core_world_snapshot.json --state-out stores/_demo/persistent_brain_state.json
```

Continue from a saved brain:

```powershell
python -m kishsyn_core.tools.run_core_world --steps 120 --state-in stores/_demo/persistent_brain_state.json --out stores/_demo/core_world_snapshot.json
```

## Storage decision

The old database layer stays out for now. The active state store is explicit JSON and report history is JSONL. That is intentional: M1-M3 anatomy contracts are still becoming stable. Indexed database storage comes back only as its own milestone when the contracts are stable and scale pressure proves the need.

## Future direction

M4 should be **Sensory Adapter Quarantine and Multimodal Grounding**. Screen, image, audio, keyboard, console, files, math symbols, and tutor services should enter as replayable sensory adapters into the same MomentFrame contract. They must not bypass focus, binding, intent, prediction, consequence, or graph learning.


## v029 M4: Sensory Adapter and Expression Surface

M4 adds the first governed bridge for external surfaces. Console, math, screen, image, audio, and future hardware signals now normalize through `SensoryAdapterHub` into normal sensory features. Those features pass through FocusGate, MomentFrame, binding, anatomy growth, graph plasticity, and the neural atlas.

Expression is now a motor surface, not a chatbot mask. `ExpressionSurface` emits compact graph-grounded console output from need/action/prediction/outcome evidence. The `NeuralAtlasProjector` standardizes how all touched surfaces appear in the GUI so the visible synapse graph can mirror her developing associative anatomy.


## v030 M5: Neural Atlas Inspector and Synapse Introspection

M5 adds `kishsyn_core/atlas_inspector.py`, the read-only inspection contract for the brain-mirror GUI. The Observatory can now inspect neurons and synapses through standardized payloads instead of custom visualization hacks.

The graph canvas supports click inspection for nodes and synapses. A node inspection shows surface, kind, label, activation, age, inbound/outbound pathways, connected nodes, and recent plasticity. A synapse inspection shows source/target provenance, weight, update count, polarity, connected endpoint nodes, and recent plasticity.

Run the M5 lock:

```powershell
python -m kishsyn_core.tools.run_milestone_m5_lock --steps 128 --seeds 337 --out stores/_demo/milestone_m5_lock_report.json
```

The active milestone stack is now M1 focus/moment, M2 cross-modal intent, M3 counterfactual replay, M4 sensory adapter/expression, and M5 atlas inspection.


## v031 M6: Emotional Regulation Field

M6 adds `kishsyn_core/emotion.py`, a governed regulation-weather layer. It observes completed ticks and computes arousal, valence, control, safety, uncertainty, curiosity, fatigue, frustration, relief, and confidence from body pressure, prediction fit/mismatch, outcome, self-causation, world-causation, focus overload, planning alignment, and intent state.

The field records replayable samples, accumulates slow trait tendencies, and writes graph-visible `emotion` neurons and synapses. The Observatory now shows dominant emotion mode, regulation dimensions, and top traits inside the Focus / Action / Moment panel, and the atlas can inspect emotion nodes like any other surface.

Run the M6 lock:

```powershell
python -m kishsyn_core.tools.run_milestone_m6_lock --steps 160 --seeds 337 --out stores/_demo/milestone_m6_lock_report.json
```

The active milestone stack is now M1 focus/moment, M2 cross-modal intent, M3 counterfactual replay, M4 sensory adapter/expression, M5 atlas inspection, and M6 emotional regulation.


## v032 M7: Emotion-Biased Attention, Expression, and Memory Economy

M7 adds a bounded `EmotionBiasContract` exported from the previous emotional regulation sample into the next FocusGate and ExpressionSurface pass. Emotion may now gently bias what is noticed and may appear in expression evidence, but it still cannot choose actions, invent goals, overwrite memory, or become a personality mask.

The planning graph now stores reusable `plan_template:*` neurons instead of durable tick-specific `plan:t...` nodes. Individual plan reports remain bounded audit history. Repeated plan instances strengthen reusable anatomy, which keeps graph growth tied to meaningful novelty instead of raw tick count.

Run the per-patch gate manifest for the active patch surface:

```powershell
python -m kishsyn_core.tools.patch_gates --profile current --run
```

Run the M7 lock:

```powershell
python -m kishsyn_core.tools.run_milestone_m7_lock --steps 160 --seeds 337 --out stores/_demo/milestone_m7_lock_report.json
```

The forward path after M7 is contextual affordance cognition: object files, actor/body profiles, world-rule contexts, provenance tags, transfer inhibition, retention pressure, and common-sense use differences such as apples healing in one game, being scenery in another, serving as ingredients in another, and being food-for-others or seed-source in a robot body context.




## v034 M8: Contextual Affordance Hardening

v034 adds `AffordanceBiasContract`, a non-command contract that lets contextual affordance evidence report small local ranking pressure while keeping cross-context transfer inhibited. Game evidence can no longer imply robot-body self-edibility.

The Apple Across Worlds benchmark is now part of the controlled suite and the M8 lock probe. It proves one apple-like object kind can share reusable category anatomy while preserving different affordances across game-avatar, robot-body, healing-game, scenery-game, crafting-game, and robot-world contexts.

Run the M8 lock:

```powershell
python -m kishsyn_core.tools.run_milestone_m8_lock --steps 180 --seeds 337,171,23 --out stores/_demo/milestone_m8_lock_report.json
```

## v033 M8: Contextual Affordance Cognition Started

v033 adds `kishsyn_core/contextual_affordance.py`, the first conservative layer for common-sense meaning-in-use.

The active law is:

```text
concept + actor/body + world context + action + provenance + outcome = meaning-in-use
```

This lets the system keep separate records for cases like: apple heals a game avatar in one world, apple is scenery in another, apple is an ingredient in another, and apple is food-for-others / seed-source for a robot body. The layer records evidence and writes graph-visible affordance anatomy, but it does not command behavior yet.

Run the focused M8 test:

```powershell
python -m pytest kishsyn_core/tests/test_contextual_affordance.py -q
```

Forward milestone docs:

- `docs/MILESTONE_M8_CONTEXTUAL_AFFORDANCE_COGNITION.md`

## v035 M9: Object-File Cortex

v035 adds `kishsyn_core/object_file.py`, the first object identity layer. M8 established that affordance meaning is context-bound. M9 establishes that same kind does not mean same individual.

Apple A and Apple B may share one apple-like object-kind signature while keeping separate object files for size, blemish, location, action history, outcome history, and transformation state. Repeated sightings update the same `ObjectFile`; they do not become new durable identities.

Run the M9 lock:

```powershell
python -m kishsyn_core.tools.run_milestone_m9_lock --steps 180 --seeds 337,171,23 --out stores/_demo/milestone_m9_lock_report.json
```

Forward milestone docs:

- `docs/MILESTONE_M9_OBJECT_FILE_CORTEX.md`

Next target: M10 Retention Pressure and Memory Economy, where object files, traces, affordance records, and summaries begin earning permanence through value, repetition, surprise, usefulness, instruction pressure, and emotional/regulatory weight.


## v036 M10: Retention Pressure, Memory Economy, and Future OS Embodiment Doctrine

v036 adds `kishsyn_core/memory_economy.py`, a governed retention-pressure layer. It observes completed traces after lived outcome and decides whether the experience is transient, summarized, preserved, or consolidated. Repeated experience strengthens reusable `memory_summary:*` anatomy instead of creating tick-specific `memory:t...` nodes.

The law is now embedded in code and tests:

```text
graph = reusable anatomy
ledger = bounded event history
retention pressure = what earns durable memory
```

v036 also adds `kishsyn_core/external_interface.py`, a pure contract layer for future OS/program embodiment. It does not move the mouse, type keys, browse, call APIs, or control programs. It defines the adapter safety envelope future surfaces must obey: observe first, propose second, supervised dummy actuation only after gated certification, and explicit grants before any write-like action.

Run the M10 lock:

```powershell
python -m kishsyn_core.tools.run_milestone_m10_lock --steps 180 --seeds 337,171,23 --out stores/_demo/milestone_m10_lock_report.json
```

Run focused tests:

```powershell
python -m pytest kishsyn_core/tests/test_memory_economy.py kishsyn_core/tests/test_external_interface.py -q
```

Next path: M11 should turn play into a governed developmental pressure: safe-enough body state, novelty, uncertainty, low risk, experimental action, prediction, outcome, and learning progress. External OS/program interaction stays future-facing until the adapter contracts and dummy benches are mature.


## Current Milestone Direction: M14 Interface Affordance Discovery

M13 made desktop/program surfaces observable. M14 makes their UI elements learnable. Buttons, text fields, menus, browser surfaces, console regions, game HUD elements, and files now become reusable interface signatures and proposal-only affordance records through observation. The system may inspect and propose; write-like actions remain blocked.

The current browser Observatory remains valuable, but it is only a shell. The organism loop, adapter contracts, and `stores/` brain state must remain shell-independent so the future official Windows `.exe` can wrap the same runtime rather than forking cognition into an HTML-only path.

Next direction: M15 Dummy Bench Actuation. KishSyn should learn to propose and test mouse/keyboard/console-like actions inside a fake sandbox only, with reversible state, audit logs, and zero real OS writes.


## v039 M13: Desktop/OS Observation and Desktop Runtime Portability

v039 adds `kishsyn_core/desktop_observation.py`, the read-only OS/program observation substrate. It accepts replayable `DesktopObservationFrame` values, registers external surfaces through `ExternalAdapterRegistry`, emits sensory packets through `SensoryAdapterHub`, and writes reusable graph anatomy like `external_surface:*`, `external_app:*`, `ui_role:*`, and `ui_label:*`.

It also adds `kishsyn_core/runtime_shell.py`, which locks the portability rule: web Observatory, headless CLI, and future official desktop `.exe` are shells over the same organism loop and `stores/` brain state. HTML may render the current Observatory, but it may not own cognition.

Run the M13 lock:

```powershell
python -m kishsyn_core.tools.run_milestone_m13_lock --steps 180 --seeds 337,171,23 --out stores/_demo/milestone_m13_lock_report.json
```

Focused tests:

```powershell
python -m pytest kishsyn_core/tests/test_milestone_m13_os_observation.py -q
```


## v040 - M14 Interface Affordance Discovery

- Added `kishsyn_core/interface_affordance.py` with `UIElementSignature`, `InterfaceAffordanceRecord`, `InterfaceAffordanceContract`, and `InterfaceAffordanceCortex`.
- Integrated interface affordance discovery into desktop/OS observation ingestion as an optional governed surface.
- Added interface-affordance snapshot metrics, score metrics, and JSON brain-state persistence.
- Added `kishsyn_core/tools/run_milestone_m14_lock.py` and `kishsyn_core/tests/test_milestone_m14_interface_affordance.py`.
- Updated patch gates to prove UI affordance records form, write-like candidates stay blocked, and no `ui:t*` tick-node leaks appear.
- Added `docs/MILESTONE_M14_INTERFACE_AFFORDANCE_DISCOVERY.md`.
- Safety: M14 grants no mouse, keyboard, scroll, file, API, browser, game, console, shell, or program actuation. It discovers proposal-only affordances for future dummy benches.

Validation used for this patch:

```powershell
PYTEST_DISABLE_PLUGIN_AUTOLOAD=1 python -m pytest kishsyn_core/tests/test_milestone_m14_interface_affordance.py -q
PYTEST_DISABLE_PLUGIN_AUTOLOAD=1 python -m pytest kishsyn_core/tests/test_milestone_m13_os_observation.py kishsyn_core/tests/test_external_interface.py kishsyn_core/tests/test_dev_gates_inventory.py -q
python -m kishsyn_core.tools.run_milestone_m14_lock --steps 120 --seeds 337,171,23 --out stores/_demo/milestone_m14_lock_report.json
python -m kishsyn_core.tools.patch_gates --profile current --run
```


### v041 synaptic viewport performance doctrine

The Observatory graph panel now treats rendering as a bounded camera over KishSyn anatomy. Full graph state remains in the organism and `stores/`, while web/desktop shells should request a budgeted projection for live rendering. Use `/api/snapshot?graph=full` only for diagnostics. The default web snapshot path uses the budgeted viewport projection so growth in the brain does not force the browser to draw every neuron and synapse every frame.


## M15 Dummy Bench Actuation

M15 adds a sealed in-memory dummy desktop where proposal-only interface affordances can execute safely. It lets KishSyn learn from click/type/read-like consequences without real OS, file, shell, browser, API, mouse, keyboard, or physical authority. Real surfaces remain observation/proposal-only until later supervised grants.
