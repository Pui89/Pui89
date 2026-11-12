# PUI89 — Evidence-Led AI & Robotics Engineering

**Intelligent systems. Verifiable decisions. Safer outcomes.**

PUI89 is an independent AI and robotics research initiative based in Thailand. It develops software foundations, applied AI experiments and robotics concepts across agriculture, disaster response, multimodal inspection, home safety and intelligent mobility.

🌐 **Official portfolio:** https://pui89.github.io/  
🇹🇭 **Thai portfolio:** https://pui89.github.io/th.html  
🧭 **Engineering Atlas:** https://pui89.github.io/engineering-atlas.html  
🧠 **Shared AI Core:** https://pui89.github.io/ai-core.html  
📚 **GitHub projects:** https://github.com/Pui89

## Platform architecture: Shared AI Core

The **Shared AI Core is PUI89's cross-project engineering platform, not an eighth product**. Its purpose is to establish reusable interfaces and safety/evidence practices that individual projects can adopt as they mature.

The architecture is organized around four common contracts:

- **Observation** — a sourced input with timestamp, modality, quality and provenance.
- **WorldState** — a time-aware interpretation of the available observations, including uncertainty and missing information.
- **ActionProposal** — a bounded recommendation that can be reviewed before any consequential action.
- **FailureReport** — a structured record of faults, degraded operation, rejected inputs and recovery evidence.

Cross-project engineering priorities include evidence traceability, uncertainty-aware reasoning, explicit abstention, safe-hold behavior, fault injection, reproducible tests and human approval for critical actions. These are design and implementation priorities; each repository documents what is actually implemented and tested.

## Seven-project portfolio

| Project | Focus | Project page |
|---|---|---|
| [Coconut Harvest AI](https://github.com/Pui89/Coconut-Harvest-AI) | Coconut maturity assessment, visual perception and harvesting-robot research | [Website](https://pui89.github.io/coconut.html) |
| [Extreme Flood Rescue AI](https://github.com/Pui89/Extreme-Flood-Rescue-AI) | Flood situational awareness, terrain evidence and rescue-robot research | [Website](https://pui89.github.io/flood-rescue.html) |
| [Multimodal Narcotics Screening AI](https://github.com/Pui89/Multimodal-Narcotics-Screening-AI) | Multimodal screening research, evidence provenance and human review | [Website](https://pui89.github.io/screening.html) |
| [AI HOME — Home Safety](https://github.com/Pui89/AI-Home-Safety-Robot) | Home-condition awareness and safety-assistance software/robotics concept | [Website](https://pui89.github.io/home.html) |
| [AI NOMAD — Mobile Assistant](https://github.com/Pui89/AI-Mobile-Assistant-Robot) | Compact mobile-assistant and outdoor mobility concept | [Website](https://pui89.github.io/nomad.html) |
| [AI Robot Car](https://github.com/Pui89/AI-Autonomous-Robot-Car) | Vehicle perception, mobility context and safety-assistance research | [Website](https://pui89.github.io/ai-robot-car.html) |
| [EasyRide AI Step-Through Scooter](https://github.com/Pui89/AI-Motorcycle-Robotics) | AI-assisted step-through mobility and road/flood safety research | [Website](https://pui89.github.io/ai-robot-motorcycle.html) |

## Engineering roadmap

Work is intended to progress through evidence gates rather than unsupported completion percentages:

1. **Shared foundations** — define and test common data contracts, provenance, uncertainty and failure handling.
2. **Software evaluation** — build reproducible tests and record datasets, licences, metrics and limitations.
3. **Simulation and controlled experiments** — evaluate scenarios, edge cases and failure behavior; label simulated results clearly.
4. **Hardware integration** — proceed only when resources, safety controls and test plans are available.
5. **Field validation** — report real-world performance only after documented, repeatable testing; address applicable safety and regulatory requirements before deployment.

A roadmap item is not a claim that the gate has been passed. Current evidence and project-specific status belong in the relevant repository and project page.

## Evidence and development status

PUI89 distinguishes:

- **Implemented software** — code exists in the repository.
- **Tests run** — tests have actually executed; results and scope should be recorded.
- **Synthetic or simulated evaluation** — results are limited to the stated synthetic or simulated conditions.
- **Proposed design** — a concept, architecture or engineering target that is not yet demonstrated.
- **Validated physical performance** — supported by documented tests on physical hardware under stated conditions.

A passing software test does not establish real-world model accuracy, robot capability, operational safety, safety certification or commercial readiness. Physical performance claims require relevant test evidence. Concepts and engineering targets must remain labelled as such.

The portfolio follows an open-source-first, resource-conscious approach. Third-party code, models, datasets and checkpoints require separate licence, provenance, security and hardware-resource checks before adoption.

## Collaboration and contributions

PUI89 welcomes constructive research and engineering collaboration in applied AI, computer vision, multimodal systems, robotics, simulation, safety engineering and evidence-based evaluation.

To contribute:

1. Read the relevant repository README and existing issues.
2. Open an issue to discuss a proposed change before substantial work.
3. Submit focused pull requests with a clear rationale, test instructions and evidence.
4. Identify limitations, data/model provenance and whether results are real, synthetic or simulated.

Contributions should be documented, reviewable and testable. No contribution should imply that a prototype is field-ready or safety-certified without supporting evidence.

---

<sub>Independent research and engineering initiative · Thailand · Evidence-led · Safety-conscious · Open-source-first</sub>
