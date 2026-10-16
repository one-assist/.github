# One Assistant

One develops tooling and research focused on audio-driven assistants and compact classification engines. This organization brings together two complementary projects that address audio capture, transcription and downstream classification.

## Projects

- One — Voice assistant and transcription
  - Repository: https://github.com/one-assist/One
  - Short description: A Python-based voice assistant that uses fast-whisper for on-device or server transcription and processing.
  - Primary focus: audio capture and transcription workflows, assistant orchestration and integration with voice models.

- One-classifier — Frequency-based vectorization and classification engine
  - Repository: https://github.com/one-assist/One-classifier
  - Short description: A C++ library and toolset implementing frequency-based vectorization and classification algorithms for compact, high-performance classification workloads.
  - Primary focus: efficient feature extraction and classification for constrained environments or high-throughput pipelines.

## How these projects relate

One and One-classifier are complementary: One focuses on audio capture and transcription while One-classifier provides lightweight, performant classification capabilities that can be applied to transcripts, features, or other extracted signals. They are maintained as separate repositories to allow independent development and language/runtime choices, while enabling integration where appropriate (for example, using One-classifier as an external service or native module for intent classification).

## Quick start

- To evaluate the voice assistant:
  1. Visit https://github.com/one-assist/One and follow that repository's README for installation and runtime instructions.
- To evaluate the classifier:
  1. Visit https://github.com/one-assist/One-classifier and follow that repository's README for build and usage instructions.

## Contribution and governance

- Each repository contains its own contributor guidelines, issue tracker, and CI. Please open issues or pull requests in the repository you are contributing to.
- If you are unsure where to file a report or proposal, open an issue in the relevant project; maintainers will triage or redirect as needed.

## Licensing and notices

- See each repository for its license file. Notably, the One repository lists an MIT License; confirm license files in each project before reuse.

## Contact

For coordination across the organization (roadmap, cross-repo integration, governance), please open an issue in the repository most relevant to your proposal; maintainers will consolidate cross-cutting discussions as needed.
