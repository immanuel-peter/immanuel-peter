# Immanuel Peter

![Profile Views](https://komarev.com/ghpvc/?username=immanuel-peter)

## About Me

Computer Science + Physics at the University of Chicago. Incoming Member of Technical Staff Intern at Tensormesh.

## Links

- Portfolio: [ipeter.dev](https://ipeter.dev)
- Resume: [ipeter.dev/resume.pdf](https://ipeter.dev/resume.pdf)
- LinkedIn: [linkedin.com/in/immanuel-peter](https://www.linkedin.com/in/immanuel-peter)
- GitHub: [github.com/immanuel-peter](https://github.com/immanuel-peter)
- Hugging Face: [huggingface.co/immanuelpeter](https://huggingface.co/immanuelpeter)
- Email: `ipeter@uchicago.edu`

## Current Work

- Joining Tensormesh to work alongside the team behind LMCache on inference infrastructure.
- Interested in software engineering, developer infrastructure, and self-driving neural networks.

## Selected Projects

### Hostess
Hostess is a deployment platform for multi-service applications built around a declarative `hostess.yml`. It combines a Go CLI, control plane, and Studio dashboard to deploy full stacks like Next.js, FastAPI, Postgres, and Redis with generated Kubernetes manifests, service discovery, secrets wiring, per-service deploys, and framework-specific operational views.

- Live: [hostess.sh](https://hostess.sh)
- Stack: Go, Kubernetes, Next.js, PostgreSQL, GCP, Docker

### Redis Operator
A Kubernetes Redis operator inspired by CloudNativePG's control-plane design. It manages pods and PVCs directly instead of relying on StatefulSets, which lets it enforce fencing-first failover, replica-first rolling updates, pod-level instance management, backup workflows, and deterministic behavior across standalone, sentinel, and cluster modes.

- Source: [howl-cloud/redis-operator](https://github.com/howl-cloud/redis-operator)
- Stack: Go, Kubernetes, Redis, Helm, Prometheus

### AutoMoE
A modular self-driving research stack built around a Mixture-of-Experts architecture instead of a single end-to-end model. The repo includes data pipelines for BDD100K, nuScenes, and CARLA, specialized perception experts, a context-aware gating network, a trajectory policy head, and released CARLA datasets on Hugging Face. The final integrated simulation stage is paused, but the project captures the full training, evaluation, and research workflow.

- Write-up: [Building AutoMoE](https://ipeter.dev/blog/moe-self-driving)
- Source: [immanuel-peter/self-driving-model](https://github.com/immanuel-peter/self-driving-model)
- Stack: Python, PyTorch, DDP, CUDA, CARLA, Hugging Face

### Matchbox
An AI-powered research matching platform that connects students with labs using semantic search and LLM-based fit scoring. It replaces fragmented outreach with a centralized pipeline for discovery, parsing, ranking, and review.

- Write-up: [Inside the Architecture of Matchbox](https://ipeter.dev/blog/matchbox)
- Stack: Next.js, FastAPI, ChromaDB, GCP, OpenAI API

### Grok Review
A small product that turns a public GitHub pull request URL into a streaming AI code review with line-by-line feedback.

- Live: [grokreq.com](https://grokreq.com)
- Source: [immanuel-peter/grok-review](https://github.com/immanuel-peter/grok-review)
- Stack: Next.js, TypeScript, GitHub API, xAI API

## Experience

### Tensormesh
Incoming Member of Technical Staff Intern. Tensormesh helps enterprises reduce GPU cost by offloading reusable KV caches during inference.

### Quantum Rings
Software Engineer Intern. Delivered 19 PRs and 43 contributions across schema refactors, queue-driven execution processing, telemetry aggregation with AWS SQS + TypeORM, and full-stack analytics dashboards with NestJS, Next.js, and Recharts.

## Writing

- [Inside the Architecture of Matchbox](https://ipeter.dev/blog/matchbox)
- [Building AutoMoE](https://ipeter.dev/blog/moe-self-driving)
