# TheoremFlow

**AI-assisted mathematical video generation and lesson quality assurance.**

TheoremFlow is a portfolio project based on the open-source Proof to Video workflow. Its goal is to make mathematical video production easier to inspect, validate, and reproduce through a structured pipeline for mathematical explanations, animation, narration, subtitles, and video rendering.

## Project goals

- Generate narrated mathematical lessons using animated visualizations.
- Organize lesson content into chapters and synchronized subtitles.
- Validate generated media and identify missing assets or timing problems.
- Improve reproducibility, testing, and developer experience.
- Explore a dashboard for inspecting lesson-generation results.

Features listed as goals are planned enhancements and may not yet be implemented.

## Technology stack

- **Python** — workflow orchestration and tooling
- **Manim** — mathematical animations
- **Kokoro** — local text-to-speech
- **FFmpeg** — audio and video processing
- **LaTeX** — mathematical typesetting
- **pytest** — automated testing

## Getting started

This project is under active development. Follow the setup instructions in the existing documentation and `environment.yml`. Review the original project's setup requirements before running the supplied example.

## Development roadmap

1. Establish a reproducible local setup.
2. Understand and document the existing rendering pipeline.
3. Add automated checks for lesson structure and media quality.
4. Expand test coverage and improve error handling.
5. Explore a dashboard and reproducible deployment workflow.

## Project background and attribution

The initial implementation is based on [Proof to Video](https://github.com/ANRGUSC/proof2video), created by **Bhaskar Krishnamachari**.

This repository is an independent development workspace for learning, extending, and documenting the software. The original implementation should not be mistaken for entirely original authorship by the maintainer. New features and modifications will be documented as they are implemented.

See [`LICENSE`](LICENSE), [`PROVENANCE.md`](PROVENANCE.md), and [`THIRD_PARTY_NOTICES.md`](THIRD_PARTY_NOTICES.md) for licensing, provenance, and third-party notices.

## Current status

Early development. The first milestone is to reproduce the existing example, understand the architecture, and add verified improvements with tests.


