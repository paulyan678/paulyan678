# Paul Yan

I'm a UC San Diego M.S. student in Computer Science and Engineering and a University of Toronto Engineering Science graduate. I work on backend systems, machine learning research, and embedded verification. Previously, I was an ASIC verification intern at NETINT Technologies.

**Seeking Summer 2027 software engineering and ML engineering internships.** · [enyan@ucsd.edu](mailto:enyan@ucsd.edu)

## Featured work

### [OnlineOrder](https://github.com/paulyan678/full-stack-projects/tree/main/onlineorder)

**Java · Spring Boot · PostgreSQL · React**

A restaurant-ordering demo with session authentication, exact decimal cart totals and checkout. Cart writes use row locks; reads use a database snapshot so totals and line items stay consistent during concurrent checkout. Mutable carts are not cached. The PostgreSQL test lane exercises concurrent updates and delayed reads separately from the H2 API tests.

[Implementation and setup](https://github.com/paulyan678/full-stack-projects/tree/main/onlineorder) · [Validation runs](https://github.com/paulyan678/full-stack-projects/actions)

The [application suite](https://github.com/paulyan678/full-stack-projects) also includes PDF question answering, a Go media service, and an Android audio demo. Each app documents its local behavior and the provider/device boundaries that need separate validation.

### [Rotation-angle signatures](https://github.com/paulyan678/rotation-angle-signatures)

**Python · PyTorch · MoCo v2 · SimCLR**

First-author NeurReps 2025 work on fixed-angle contrastive pretraining across 16 datasets and eight encoder families. The public package contains 256 checksummed response curves: 921,600 measurements.

The repository distinguishes the published study from the current reconstruction. Its current curve-origin classifiers do not reproduce the published values recorded in the reference table; that gap remains explicit rather than being treated as a successful reproduction.

[Paper record](https://neurips.cc/virtual/2025/136911) · [Methods and assumptions](https://github.com/paulyan678/rotation-angle-signatures/blob/main/docs/METHODS_AND_ASSUMPTIONS.md) · [Validation runs](https://github.com/paulyan678/rotation-angle-signatures/actions)

### [Autonomous beach sampling](https://github.com/paulyan678/beach_sampling)

**Python · PyTorch · Bayesian inference · Reinforcement learning**

Independent follow-up work in 2026, after my 2024 research assistantship at UT Austin with Prof. Christian Claudel. The simulation combines Gaussian belief updates with masked Rainbow-DQfD for informative path planning.

Across 1,024 paired held-out procedural profiles, three validation-selected agents reached **1.997x random sampling's information gain** (95% CI: 1.974-2.022), or **97.3% of a greedy planner**. These are simulated results. The committed episode rows reproduce the summary; original trained weights are not included, so that arithmetic check is distinct from rerunning the learned agents.

[Result provenance and raw data](https://github.com/paulyan678/beach_sampling/tree/main/results/research) · [Validation runs](https://github.com/paulyan678/beach_sampling/actions)

## Systems projects

- **[CoVRL](https://github.com/paulyan678/covrl):** a public codec-neutral verification prototype developed during my NETINT internship. It includes Python regression orchestration, UVM source, and a 135-action RL prototype over 90 mock coverage goals. Portable RTL, Python/mock execution, and licensed UVM validation are reported separately. Mock policy results are not evidence of RTL coverage improvement.
- **[Smart Shovel](https://github.com/paulyan678/smart-shovel):** an embedded sensing/logging prototype with an Arduino-independent core, timing and recovery tests, and reproducible orientation calibration. The grams-per-millivolt factor remains provisional pending physical known-mass validation; a firmware build does not establish measurement accuracy.
- **[Cerberus](https://github.com/paulyan678/cerberus):** a team capstone on long-video event retrieval. The repository preserves collaborator credit and separates the offline fictional fixture from evaluation on real annotated video.

## Technical focus

- **Languages:** Python, Java, Go, JavaScript, Kotlin, C/C++, SQL, SystemVerilog
- **Tools:** PyTorch, Spring Boot, React, PostgreSQL, Jetpack Compose, UVM, PlatformIO, Docker, GitHub Actions

The linked repositories contain setup commands, design tradeoffs, reproducible checks and current limitations. Validation results should be read with their source revision and execution environment.
