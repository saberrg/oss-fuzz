# OSS-Fuzz Workflow Study Status

Status: workflow study / integration planning. This fork should not be described as an accepted upstream OSS-Fuzz integration unless a merged upstream PR exists.

## Purpose

This fork is used to study OSS-Fuzz project structure, sanitizer integration, Docker-based build conventions, and continuous fuzzing workflows relevant to MQTT/NanoMQ fuzzing research.

## Application-Relevant Framing

Use this repository as evidence of OSS-Fuzz workflow familiarity, not as evidence of upstream project acceptance.

Accurate wording:

- Studying OSS-Fuzz-style integration patterns.
- Applying continuous fuzzing conventions to an in-progress NanoMQ/MQTT fuzzing capstone.
- Planning or experimenting with integration paths for libFuzzer targets.

Avoid:

- "Accepted into OSS-Fuzz."
- "Merged upstream."
- "OSS-Fuzz found vulnerabilities in NanoMQ through my integration."

## Connection To Research Proposal

The Anthropic Fellows proposal uses OSS-Fuzz-style expectations as part of the evaluation bar for LLM-guided fuzzing:

- deterministic build instructions
- sanitizer-enabled execution
- clear target binaries
- corpus and dictionary handling
- reproducible crash triage
- no unsupported vulnerability claims
