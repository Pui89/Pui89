# PUI89 — Independent Industrial AI Platform

<p align="center">
  <strong>🇬🇧 English</strong> · <a href="README.th.md">🇹🇭 ภาษาไทย</a>
</p>

**Developed independently in Thailand · Open to global technical collaboration**

PUI89 is an independently developed, software-first Industrial AI initiative. It explores reusable AI software, intelligent systems, robotics concepts, and software–hardware integration across agriculture, inspection, assistance, and mobility.

PUI89 is hardware-neutral. The focus is on making AI workloads work efficiently and reliably across CPUs, GPUs, NPUs, MCUs, sensors, embedded systems, and edge-computing platforms. PUI89 does not manufacture semiconductor chips.

## Technology collaboration

PUI89 welcomes technical enquiries and potential evaluation proposals from:

- Startups developing AI hardware, robotics, sensors, and computing technologies.
- Hardware manufacturers and technology companies.
- Universities and independent research institutes.
- AI developers, engineering teams, and open-source communities.

### Bring your hardware. Explore technical evaluation with PUI89.

Companies, startups, and technology developers are welcome to propose bringing their own compatible hardware for a potential technical evaluation with PUI89.

Potential evaluation areas include CPU, GPU, NPU, MCU, and AI accelerator integration; edge AI and local inference; model selection, sizing, and quantisation; multimodal sensors and robotics components; hardware–software compatibility; resource efficiency; reliability; fault handling; and reproducible testing.

Any evaluation is subject to technical suitability, available capacity, safety requirements, and mutually agreed written conditions. PUI89 does not promise to accept or test every offered device.

## Independent development and relationship disclosure

PUI89 operates independently. Its public materials do not imply endorsement, sponsorship, affiliation, employment, representation, or an existing partnership with any government agency, university, research institute, company, or other organisation.

An enquiry, discussion, contribution, or proposed test does not establish a partnership. Any collaboration must be separately reviewed and agreed in writing by the relevant parties. Names and logos of organisations will not be presented as partners or supporters without appropriate permission and confirmation.

## Contact

**Email:** [puinuanmanee@gmail.com](mailto:puinuanmanee@gmail.com?subject=PUI89%20Technical%20Collaboration)

When contacting PUI89, please briefly describe your organisation or technical background, the hardware or technology proposed, the intended evaluation, and any conditions or expectations.

🌐 **Official website:** https://pui89.github.io/  
🇹🇭 **Thai website:** https://pui89.github.io/th.html  
🧭 **Engineering Atlas:** https://pui89.github.io/engineering-atlas.html  
🧠 **Shared AI Core:** https://pui89.github.io/ai-core.html

## Founder and initiative identity

PUI89 is a founder-led independent initiative. The Founder sets the initiative's direction, priorities, and decisions while drawing on AI tools, research, specialist knowledge, and collaboration.

**AI Engineering** describes a technical discipline and development process; it is not used here as the Founder's job title or as a claim of a professional engineering qualification.

Read the [PUI89 Founder & Initiative Identity](https://pui89.github.io/founder.html).

## Platform architecture: Shared AI Core

The **Shared AI Core is PUI89's cross-project engineering platform, not a standalone product**. Its purpose is to establish reusable interfaces and safety/evidence practices that individual products can adopt as they mature.

The architecture is organized around four common contracts:

- **Observation** — a sourced input with timestamp, modality, quality and provenance.
- **WorldState** — a time-aware interpretation of the available observations, including uncertainty and missing information.
- **ActionProposal** — a bounded recommendation that can be reviewed before any consequential action.
- **FailureReport** — a structured record of faults, degraded operation, rejected inputs and recovery evidence.

Cross-project engineering priorities include evidence traceability, uncertainty-aware reasoning, explicit abstention, safe-hold behavior, fault injection, reproducible tests and human approval for critical actions. These are design and implementation priorities; each repository documents what is actually implemented and tested.

## Six-product portfolio

| Product | Focus | Project page |
|---|---|---|
| [Coconut Harvest AI](https://github.com/Pui89/Coconut-Harvest-AI) | Coconut maturity assessment, visual perception and harvesting-robot research | [Website](https://pui89.github.io/coconut.html) |
| [PUI89 Sentinel — All-Terrain Inspection Robot](https://github.com/Pui89/PUI89-All-Terrain-Inspection-Robot) | Four-legged quadruped inspection concept, environmental awareness and human-supervised evidence capture | [Website](https://pui89.github.io/sentinel.html) |
| [PUI89 AI HOME](https://github.com/Pui89/AI-Home-Safety-Robot) | Indoor home-condition awareness and evidence-led assistance | [Website](https://pui89.github.io/home.html) |
| [PUI89 AI NOMAD](https://github.com/Pui89/AI-Mobile-Assistant-Robot) | Intelligent suitcase mobile-assistant concept with a telescopic pull handle and integrated luggage-style wheels; preliminary 8–10 kg target, 10 kg maximum; physical performance not validated | [Website](https://pui89.github.io/nomad.html) |
| [PUI89 AI Global SUV](https://github.com/Pui89/PUI89-AI-Global-SUV) | Medium-size global SUV concept; HEV-first evaluation with powertrain-neutral, advisory-only AI software | [Website](https://pui89.github.io/ai-global-suv.html) |
| [PUI89 AI Step-Through Scooter](https://github.com/Pui89/AI-Step-Through-Scooter) | Rider-centred mobility intelligence and road-awareness research | [Website](https://pui89.github.io/ai-robot-motorcycle.html) |

**Portfolio boundary:** PUI89 has exactly six active products. Shared AI Core supports these products as common engineering infrastructure and is not counted as a product. Flood and road-water awareness may appear as advisory requirements within relevant mobility products, not as a separate product.

## PUI89 platform direction — software-first Industrial AI

PUI89's long-term direction is an **Industrial AI Platform** built from reusable software and engineering capabilities. The focus is to make AI systems work reliably within real product constraints—not to manufacture semiconductor chips or claim that every proposed platform capability is already implemented.

Shared engineering themes include:

- **Perception & Task Intelligence (PTI):** a traceable observe → perceive → assess → decide → respond workflow, with explicit uncertainty, abstention and human review.
- **General multimodal intelligence:** combine authorised visual, audio, text, spatial, map and time-series evidence while preserving source, timestamp, quality and modality-specific limits.
- **Heterogeneous compute intelligence:** research efficient task placement across CPU, GPU, NPU and MCU resources, memory, sensors and power constraints; evaluate model sizing, quantisation, scheduling, edge inference and safe fallback.
- **Simulation & digital-twin engineering:** use staged process, routing and robotics simulation to test assumptions before controlled prototypes; simulation is not physical validation.
- **Safety, security and recovery:** keep AI proposals separate from independent safety controls; use least privilege, traceable changes, fault reporting, recovery evidence and human approval for consequential actions.
- **Hardware and materials engineering:** record exact component identity, compatibility, manufacturer, origin evidence, supplier, dated cost and lead time before procurement decisions.
- **Open-source-first technology governance:** review provenance, licensing, security, privacy, resource needs and maintainability before adopting external code, models or datasets.

These are shared engineering priorities. Each product adopts only the capabilities relevant to its mission, and implementation or validation is claimed only when supported by repository evidence and reproducible tests.

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

<sub>Independent AI & Robotics Initiative · Thailand · Evidence-led · Safety-conscious · Open-source-first</sub>
