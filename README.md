Interaction Drift Monitor

Conceptual Python prototype for monitoring semantic drift across sustained human-AI interaction using text comparison and longitudinal evaluation methods.

This repository extends ideas from my independent research paper:

Third-Space Cognition: Interaction-Level Dynamics in Sustained Human-AI Coupling
Zenodo DOI: 10.5281/zenodo.18679265

Project Purpose

Many AI evaluation methods focus on single prompts or isolated outputs. This project explores a different question:

How can we begin measuring change across sustained human-AI interaction over time?

The goal is to prototype simple methods for comparing early-session and late-session text samples, estimating semantic drift, and documenting interaction-level changes that may not appear in one-turn evaluation.

What This Prototype Will Explore

This project is designed to model concepts such as:

* semantic drift across long-horizon interaction
* personalization drift
* changes in model response style over time
* user-model feedback dynamics
* divergence between early and late conversational patterns
* lightweight longitudinal evaluation methods

Planned Features

* Compare early-session and late-session text samples
* Calculate basic text similarity
* Generate a drift score
* Summarize changes in tone, keywords, or semantic overlap
* Export results to a simple markdown report
* Eventually support embedding-based comparison using open-source tools

Current Status

Early conceptual prototype.

The first version will use simple text comparison methods before moving toward more advanced embedding-based approaches.

Research Context

This repo is connected to my broader work in:

* human-AI interaction
* conversational AI evaluation
* Human-Computer Interaction
* personalization safety
* trust calibration
* AI safety and alignment
* qualitative research methods

Related Repository

Third-Space Cognition Dataset:
https://github.com/FlameForged/third-space-cognition-dataset

Technologies

Planned initial tools:

* Python
* basic text preprocessing
* keyword overlap
* cosine similarity
* markdown report generation

Future versions may use:

* sentence embeddings
* scikit-learn
* transformers
* visualization libraries

Disclaimer

This is an exploratory research prototype, not a production monitoring system. It is intended to translate qualitative research questions into early technical artifacts that can support future AI evaluation and HCI research.
