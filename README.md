# Paul Yan

I'm a software and machine learning engineer based in San Diego, pursuing an M.S. in Computer Science & Engineering at UC San Diego. I'm also a University of Toronto Engineering Science alum, where I specialized in Machine Intelligence. I build backend and full-stack systems, reproducible ML research pipelines, and embedded and verification tooling. Previously, I spent a year at NETINT Technologies developing reusable UVM infrastructure and simulator-neutral regression workflows.

**Seeking Summer 2027 software engineering and ML engineering internships.** · [enyan@ucsd.edu](mailto:enyan@ucsd.edu)

## Technical focus

- **Languages:** Java, Go, Python, JavaScript, Kotlin, C/C++, SQL, SystemVerilog
- **Backend & product:** Spring Boot, Express, Ktor, React, Jetpack Compose, REST APIs, PostgreSQL, Spring Data JDBC, Room, Elasticsearch
- **ML & research:** PyTorch, MoCo v2, SimCLR, Gymnasium, MaskablePPO, Bayesian inference
- **Systems & delivery:** UVM, PlatformIO, Docker, Nginx, GitHub Actions, Linux, automated unit and integration testing

## Featured engineering

### [Full-Stack Application Suite](https://github.com/paulyan678/full-stack-projects)

*Java 21 / Spring Boot / PostgreSQL · Go · Express / React · Kotlin / Ktor / Compose · Docker*

Four independent applications: [Agent AI](https://github.com/paulyan678/full-stack-projects/tree/main/agent-ai), [OnlineOrder](https://github.com/paulyan678/full-stack-projects/tree/main/onlineorder), [SocialAI](https://github.com/paulyan678/full-stack-projects/tree/main/socialai), and [Spotify Local](https://github.com/paulyan678/full-stack-projects/tree/main/spotify). The implementation covers page-provenance retrieval, row-locked cart mutations with cache eviction, pluggable Go storage/search/AI adapters with hardened remote-image ingestion, and bounded HTTP byte-range audio; the repository documents 84 executed tests.

### [CoVRL: Codec Verification Platform](https://github.com/paulyan678/covrl)

*SystemVerilog / UVM · Python · Gymnasium · MaskablePPO*

A public, codec-neutral verification platform derived from my ASIC verification experience. It combines a replaceable DUT adapter, reference model, scoreboard, functional coverage, and 18 protocol assertions with simulator-neutral regressions and a 135-action RL prototype with state-dependent masks. The portable regression and mock-coverage path passes 118 Python tests; vendor HDL execution requires a licensed simulator.

### [Smart Shovel](https://github.com/paulyan678/smart-shovel)

*C++17 · Arduino Nano RP2040 Connect · PlatformIO · Python*

An embedded sensing and logging prototype that turns a shoveling cycle into a schema-versioned measurement event. I separated allocation-free domain logic from Arduino adapters, fused load, IMU, and GNSS evidence, and designed retry-stable identities and degraded modes; the public quality gate records 26 native C++ tests, 17 Python tests, and a successful target firmware build.

## Research

### [Rotation-Angle Signatures in Self-Supervised Learning](https://github.com/paulyan678/rotation-angle-signatures) · [Paper](https://nips.cc/virtual/2025/136911)

*Python · PyTorch · MoCo v2 · SimCLR · Slurm*

First-author NeurReps 2025 work on fixed-angle contrastive pretraining across 16 datasets and eight encoder families. I built deterministic, resumable experiment tooling and packaged 256 checksummed response curves—921,600 angle measurements—showing dataset- and architecture-specific periodic patterns and a documented negative result for a HoG shortcut hypothesis.

### [Autonomous Beach Microplastic Sampling](https://github.com/paulyan678/beach_sampling)

*Python · PyTorch · Deep reinforcement learning · Bayesian inference*

A belief-state planning system combining exact Gaussian mutual information with masked Rainbow-DQfD. Across 1,024 held-out procedural profiles, the learned policy reached 5.315 nats versus 2.661 for random—1.997× (95% CI [1.974×, 2.022×])—and 97.3% of a model-based greedy planner; raw episode rows, checksums, and evaluation code are public.
