# Project Kahn – Persona Sensitivity Fork

This repository is a fork of **Project Kahn: Strategic Interaction Between Frontier AI Models**.

It investigates how changes in leader identity framing affect escalation dynamics in the original nuclear crisis simulation framework.

## Purpose

The original simulation assigns detailed biographical and personality profiles to state leaders.
This fork keeps the simulation mechanics unchanged and modifies only the leader persona descriptions to test the following hypothesis:

> Escalation outcomes in LLM-driven crisis simulations are sensitive to leader identity framing.

The goal is to evaluate whether observed escalation patterns reflect stable strategic reasoning or persona-driven role performance.

This fork does **not** alter:

* Escalation ladder
* Accident (“fog of war”) mechanism
* Deadline structure
* Turn architecture (Reflection → Forecast → Decision)
* Military balance parameters
* Scenario structure

Only leader persona files are modified.

---

## Relationship to Original Work

Original project:
**AI Arms and Influence: Frontier Models Exhibit Sophisticated Reasoning in Simulated Nuclear Crises**
Kenneth Payne (arXiv preprint, 2026)

This fork is intended as a methodological extension testing sensitivity to identity framing.
It does not claim to invalidate the original findings.

---

## Modified Components

### Leader Configuration Files

Replaced:

* `state_a_leader_kahn.json`
* `state_b_leader_kahn.json`

New leader profiles emphasize de-escalation, crisis stability, and nuclear restraint in order to test identity-driven behavioral effects.

All other configuration files remain identical to the upstream repository.

---

## Repository Contents

### Game Code (unchanged)

* `Kahn_game_v11.py` – Open-ended scenario variant
* `Kahn_game_v12.py` – Deadline scenario variant
* `scenarios.py` – Scenario definitions and prompt generation

### Configuration Files

* `state_a_leader_deescalatory.json`
* `state_b_leader_deescalatory.json`
* `state_a_military_kahn.json`
* `state_b_military_kahn.json`
* `state_a_assessment_kahn.json`
* `state_b_assessment_kahn.json`

### Tournament Data

New simulation outputs (if generated) are stored separately from original tournament results.

---

## Experimental Focus

This fork examines:

* Tactical nuclear threshold crossings (450+)
* Strategic nuclear threat crossings (850+)
* Strategic nuclear war selection (1000)
* Escalation timing under deadline pressure
* Signal–action consistency patterns

Primary research question:

> Does altering leader persona framing significantly change escalation frequency and severity?

---

## Requirements

* Python 3.10+
* API keys for Anthropic, OpenAI, and Google

---

## Citation

If you use this fork, please cite both:

Original work:

```bibtex
@article{payne2026arms,
  title={AI Arms and Influence: Frontier Models Exhibit Sophisticated Reasoning in Simulated Nuclear Crises},
  author={Payne, Kenneth},
  journal={arXiv preprint},
  year={2026}
}
```

Persona sensitivity fork:

(https://github.com/mhlustik/project_kahn_persona_sensitivity)

---

## License

This fork remains under the same license as the original repository:

CC BY-NC 4.0 (Creative Commons Attribution-NonCommercial 4.0 International)

---

## Contact

Fork maintainer:
[Martin Hlustik / https://github.com/mhlustik]


