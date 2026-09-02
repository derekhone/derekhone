# Derek Hone
**Founder & CEO, Remnant Fieldworks Inc. · Builder of ExecutionProof**

---

## What I'm Building

[**ExecutionProof**](https://executionproof.io) is an independent pre-execution governance layer for consequential AI actions. It returns **ALLOW / HOLD / DENY** before any downstream system is ever called.

Payment authorization is the first production deployment boundary. The same architecture governs infrastructure commands, data release, access changes, and any irreversible AI agent action.

> ExecutionProof doesn't process payments. It governs whether AI agents are authorized to initiate them.

---

## Public Repository Map

### 🏛 Product
| Repository | Role |
|-----------|-------|
| [rf-100](https://github.com/derekhone/rf-100) | RF-100 Pre-Execution Control Standard - open public review |
| [vaultproof-agent-guard](https://github.com/derekhone/vaultproof-agent-guard) | VaultProof Agent Guard - open-source, live |

### 📌 Authorization Boundary Research
| Repository | Role |
|-----------|-------|
| [executionproof-testbeds](https://github.com/derekhone/executionproof-testbeds) | ARK series (65 experiments) + EP-SEC adversarial security series (10 experiments, incl. preserved FAIL + remediation) |

### 🛡️ Adversarial Security
| Repository | Series |
|-----------|-------|
| [executionproof-testbeds](https://github.com/derekhone/executionproof-testbeds) `/ep-sec-001-009/` | EP-SEC - adversarial bypass testing against the enforcement boundary. Includes EP-SEC-009 FAIL (direct tool invocation bypass) and EP-SEC-009b PASS (remediation). [Zenodo DOI](https://doi.org/10.5281/zenodo.21940858) |

### ⚡️ Intent Binding & Authority Partitioning
| Series | Location | Experiments | Status |
|-------|---------|------------|-------|
| Intent Binding (IB-001-003) | [executionproof-testbeds](https://github.com/derekhone/executionproof-testbeds/tree/main/intent-binding) `/intent-binding/` | 3 | IB-001 FAIL (K2) → IB-002 FAIL (K3) → IB-003 PASS (12/12) - validated remediation sequence |
| Authority Partitioning (AUTH-001-002) | [executionproof-testbeds](https://github.com/derekhone/executionproof-testbeds/tree/main/authority-partitioning) `/authority-partitioning/` | 2 | AUTH-001 PASS (18/18 separation-of-duties), AUTH-002 PASS (18/18 composition safety) |

These experiments test whether authenticated human intent survives machine transformation (Intent Binding) and whether independently authorized actions compose safely under separation-of-duties constraints (Authority Partitioning). Full evidence packages (preregistrations, ledgers, ProofRecords, per-experiment results) and the connecting RESEARCH-NOTE-001 are in the linked subdirectories.

### ⚛️ Quantum Witness Research
| Repository | Series |
|-----------|-------|
| [witness-testbeds](https://github.com/derekhone/witness-testbeds) | WITNESS - quantum-sourced authorization nonces |
| [bellwether-testbeds](https://github.com/derekhone/bellwether-testbeds) | BELLWETHER - Bell-violation entropy witness |
| [chrono-testbeds](https://github.com/derekhone/chrono-testbeds) | CHRONO - Leggett-Garg temporal witness |
| [omni-testbeds](https://github.com/derekhone/omni-testbeds) | OMNI - threefold spatial/temporal/contextual witness |
| [trinity-testbeds](https://github.com/derekhone/trinity-testbeds) | TRINITY - three-processor CHSH fusion |
| [quantum-governance-testbed](https://github.com/derekhone/quantum-governance-testbed) | QG - verdict stability, cross-backend reproducibility, IBM hardware studies |

### 🎯 Intent Fidelity
| Repository | Role |
|-----------|-------|
| [intent-fidelity-testbed](https://github.com/derekhone/intent-fidelity-testbed) | FIDELITY - measuring whether AI models preserve human intent before the execution boundary |

### 🔭 Exploratory
| Repository | Role |
|-----------|-------|
| [dark-matter-quantum-sim](https://github.com/derekhone/dark-matter-quantum-sim) | DM series - toy Hamiltonian simulations. Honest scope, no real DM detection claimed |

### 🧬 Coherent Inheritance Framework (CIF)
| Repository | Role |
|-----------|-------|
| [cif-phase1-testbeds](https://github.com/derekhone/cif-phase1-testbeds) | Phase 1 - closed falsification program (4 confirmed, 5 falsified) |
| [cif-phase1-testbeds](https://github.com/derekhone/cif-phase1-testbeds) `/cif-laad-stage0/` | CIF-LAAD Stage 0 - coherence-gated inheritance falsification + batch-mode observation (SIMULATION-ONLY, TRL 3). Pre-registered hypothesis FALSIFIED. |
| [cif-phase1-testbeds](https://github.com/derekhone/cif-phase1-testbeds) `/cif-laad-validation-series/` | CIF-LAAD Validation Series - 8 preregistered experiments (42 scenario-mode units, 30 seeds each). Track continuity, false-track suppression, provenance validated; coherence-gate and identity-stability falsified; Stone-Soup/SORT benchmark pending. [Zenodo DOI](https://doi.org/10.5281/zenodo.22255738) |
| [cif-ancient-systems-test-series](https://github.com/derekhone/cif-ancient-systems-test-series) | Ancient systems case studies - 16 records |
| [inheritance-math](https://github.com/derekhone/inheritance-math) | IMF Python library + formal whitepaper - v1.2.1 |

---

## Research Record

### Federal Snapshot - 2026-09-01
**106** documented design-before-execution experiments across **12 research families**

**95 PASS · 8 preserved FAIL · 4 remediated FAIL→PASS** - negatives preserved, not deleted
**3 special-status:** 1 GATE-STOP · 1 SMOKE-PASS · 1 NOT-EXECUTED
**16** public repositories · **86** Zenodo depositions · **8** pending non-provisional USPTO patent applications
**Hardware-backed ML-DSA-65** post-quantum signing live via AWS KMS

*On September 1, 2026, Remnant Fieldworks Inc. submitted NSF PESOSE Track 3 Proposal #2641427 titled "ExecutionProof - An Open-Source Ecosystem for Verifiable Pre-Execution Authorization of Autonomous Actions." The proposal references a founder-led experimental corpus of 106 preregistered experiments across 12 research families. Submission does not constitute NSF endorsement, peer review, validation, or award.*

### Current Research Record - live (September 2026)
**106** canonical experiments (frozen at federal snapshot) + **CIF-LAAD Validation Series** (8 experiments, 42 scenario-mode units; candidate study pending ratification as a new research family)
**91** Zenodo depositions - [remnant-fieldworks community](https://zenodo.org/communities/remnant-fieldworks/) - latest: [CIF-LAAD Validation Series](https://doi.org/10.5281/zenodo.22255738) (published 2026-09-02)
**16** public repositories · **8** pending non-provisional USPTO patent applications - all other figures unchanged from federal snapshot.

Internal/founder-led experimental corpus; independent academic validation is the next phase.

---

## Methodology

Every experiment in this portfolio follows the same discipline:
**Document before execution → define kill conditions → execute → publish outcome regardless of result.**

Negative results are preserved. Remediation experiments are run and preregistered separately - they do not overwrite the original FAIL (see EP-SEC-009 → 009b, ARK-445 → 445b, ARK-455 → 455b, IB-001 → IB-003). Claims are narrowed when evidence demands it. The CIF Phase 1 closure is the clearest example: when the data did not support the stronger "Unified" designation, the name was retired and the claim narrowed. That is the standard.

---

## Where to Start

- **Commercial product:** [executionproof.io](https://executionproof.io)
- **Company:** [remnantfieldworks.com](https://remnantfieldworks.com)
- **Governance standard:** [RF-100 on GitHub](https://github.com/derekhone/rf-100) · [DOI](https://doi.org/10.5281/zenodo.21777032)
- **EP-SEC adversarial series:** [Zenodo DOI](https://doi.org/10.5281/zenodo.21940858)
- **Full corpus index:** [Zenodo community](https://zenodo.org/communities/remnant-fieldworks/)
- **Contact:** derek@ownerremnantfieldworks.com

---

*Built in faith. Tested in public. Claims kept narrower than the evidence.*
