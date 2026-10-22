# Immanuel Peter

![](https://komarev.com/ghpvc/?username=immanuel-peter&style=flat-square)

**CS & Physics @ University of Chicago** · [ipeter.dev](https://ipeter.dev)

I work on multimodal and physical AI: large-scale training, linear algebra, and inference systems.

## Now

- MTS Intern @ [Tensormesh](https://tensormesh.ai), working on GPU management, LLM observability, and KV cache optimization for inference infrastructure.
- Deepening into distributed training and multimodal architectures

## Open source

- [LMCache](https://github.com/LMCache/LMCache): added coordinator APIs for [listing pinned cache entries](https://github.com/LMCache/LMCache/pull/4960) and [tracking per-key access counts](https://github.com/LMCache/LMCache/pull/4873).
- [vLLM Production Stack](https://github.com/vllm-project/production-stack): added [router volume mounts for read-only root filesystems](https://github.com/vllm-project/production-stack/pull/975) and [fixed the default NVIDIA runtime class](https://github.com/vllm-project/production-stack/pull/974).
- [Pyrefly](https://github.com/facebook/pyrefly): standardized the Rust [error-summary module and imports](https://github.com/facebook/pyrefly/pull/1370) from `summarise` to `summarize`.
- [Brev CLI](https://github.com/brevdev/brev-cli): authored the core [rsync-first file transfers with automatic SCP fallback](https://github.com/brevdev/brev-cli/pull/423), preserving incremental transfers for repeated copies.

## Projects

- **[Vision Tower Bench](https://ipeter.dev/blog/vision-tower-bench)** compares frozen vision towers across recognition, geometry, cross-view correspondence, and occlusion to guide tower, layer, and projector choices before multimodal training. [Code](https://github.com/immanuel-peter/vision-tower-bench) · [Towers](https://huggingface.co/collections/immanuelpeter/vision-heads)
- **[AutoMoE](https://github.com/immanuel-peter/self-driving-model)** is a 53M-parameter driving model with four perception experts, learned gating, and a trajectory policy. Trained experts on BDD100K and nuScenes, then adapted them to CARLA. Released [82K-frame multimodal](https://huggingface.co/datasets/immanuelpeter/carla-autopilot-multimodal-dataset) and [68K-frame image](https://huggingface.co/datasets/immanuelpeter/carla-autopilot-images) datasets.
- **[Hostess](https://hostess.sh)** compiles a declarative stack file into Kubernetes workloads, builds container images, provisions and wires Postgres and Redis, and creates isolated PR preview environments through a GitHub App.
- **[Redis Operator](https://github.com/howl-cloud/redis-operator)** manages Redis pods and persistent volumes directly, with standalone, Sentinel, and cluster modes and fencing-first failover to prevent split-brain.
- **[Postplan](https://github.com/immanuel-peter/postplan)** provides an easy toolchain for agents to publish HTML artifacts and static assets through an authenticated `curl` requests.

## Links

[ipeter.dev](https://ipeter.dev) · [Resume](https://ipeter.dev/resume.pdf) · [LinkedIn](https://www.linkedin.com/in/immanuel-peter) · [Email](mailto:hello@ipeter.dev)
