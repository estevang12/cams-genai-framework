# CAMS+GenAI Framework

CAMS+GenAI is a generative model-driven engineering framework designed to support the development of adaptive context-aware mobile systems operating in distributed IoT and edge computing environments.

This repository contains the research artifacts associated with the paper:

**"Generative Model-Driven Engineering for Adaptive Mobile Systems: The CAMS+GenAI Framework"**

The framework integrates domain-specific modeling, prompt-driven engineering, and generative AI to enable automated synthesis of context-aware applications.

---

# Overview

Modern mobile systems operating in IoT environments must adapt continuously to dynamic contextual conditions such as device mobility, network variability, and sensor events. Traditional model-driven engineering (MDE) approaches provide strong abstraction mechanisms but still require significant manual effort for model construction and transformation.

CAMS+GenAI introduces a hybrid development paradigm that combines:

- **Model-Driven Engineering**
- **Prompt-Driven Engineering**
- **Generative Artificial Intelligence**
- **Edge Computing Deployment**

This integration enables automated generation of DSL models, code artifacts, and deployable mobile applications.

---

# Architecture

The CAMS+GenAI framework consists of several layers:

- Prompt-driven modeling layer
- LLM-assisted model synthesis
- DSL validation and transformation
- Automated code generation
- Edge deployment infrastructure
- Runtime telemetry and feedback

These components enable the creation of adaptive mobile systems capable of operating in distributed edge–cloud environments.

---

# Repository Structure
dsl/
DSL grammar and metamodel specification

prompts/
Prompt templates and schema definitions

models/
Example DSL models and generated artifacts

code-generation/
Model-to-code transformation artifacts

edge-deployment/
Configuration for Raspberry Pi edge nodes and MQTT communication

experiments/
Experimental datasets, scripts, and evaluation artifacts

docs/
Architecture diagrams and additional documentation


---

# Experimental Evaluation

The framework was evaluated through a series of experiments using a **smart logistics scenario** involving mobile devices, IoT sensors, and edge computing nodes.

The evaluation compares the CAMS+GenAI framework with previous approaches from the CAMS family, including:

- CAMS-F
- CAMS-Edge

Evaluation metrics include:

- Model accuracy
- Prompt Consistency Score (PCS)
- Response time
- Resource usage
- Adaptation rate

---

# Reproducibility

To support reproducibility of the experimental results, this repository includes:

- DSL metamodel specification
- Prompt schema definitions
- Example context-aware models
- Code generation artifacts
- Edge deployment configuration
- Experimental evaluation scripts

---

# Citation

If you use this framework in your research, please cite:
Estevan Gomez-Torres et al.
Generative Model-Driven Engineering for Adaptive Mobile Systems:
The CAMS+GenAI Framework.


---

# License

This project is released under the **MIT License**.

---

# Research Direction

The CAMS+GenAI framework explores the intersection of:

- Model-Driven Engineering
- Generative AI
- Context-Aware Systems
- Edge Computing

Future work includes:

- DSL co-evolution mechanisms
- multi-agent reasoning for model synthesis
- autonomous model adaptation using runtime telemetry

