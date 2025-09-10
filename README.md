# Immanuel Peter – CS, Physics & Math Student at UChicago | Aspiring AI Engineer

![Profile Views](https://komarev.com/ghpvc/?username=immanuel-peter)

## About Me

- **Student at the University of Chicago** majoring in Computer Science, Physics and Mathematics.
- Focused on neural network training, machine learning infrastructure, and autonomous systems.

## Goals

- **Short term**: Become an AI Engineering intern at a top-tier AI lab (Tesla, Waymo, NVIDIA, OpenAI, Deepmind, etc.)
- **Long term**: Build developer-first platforms and found tech companies that blend deep engineering with user simplicity.

## Projects

### AutoMoE – Mixture-of-Experts Self-Driving Model

[![GitHub Repo](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/immanuel-peter/self-driving-model)

- **Description**: Developed a modular **Mixture-of-Experts (MoE)** architecture for autonomous driving within the CARLA simulator. The model combines multiple specialized perception experts (object detection, drivable area segmentation) using a learned gating network to handle diverse driving contexts.
- **Infrastructure**: Built high-performance data pipelines and multi-GPU training scripts (DistributedDataParallel) for large autonomous driving datasets including **BDD100K**, **nuScenes** and **CARLA**.
- **Status & Lessons Learned**: This project is currently paused. While the end-to-end system was completed, it fell short of performance expectations. The experience provided valuable lessons in the importance of thorough literature review, robust evaluation pipelines, and systematic hyperparameter tuning before scaling up training. The project resulted in reusable CARLA pipelines and two large-scale public datasets for the autonomous driving community. For a full breakdown, see the project's [SHORTCOMINGS.md](https://github.com/immanuel-peter/self-driving-model/blob/main/SHORTCOMINGS.md) file.

### CARLA Autopilot Multimodal Dataset

[![Hugging Face](https://img.shields.io/badge/HuggingFace-dataset-yellow?style=for-the-badge&logo=huggingface)](https://huggingface.co/datasets/immanuel-peter/carla-autopilot-multimodal-dataset)

- Large-scale multimodal dataset (~365 GB, ≈82k frames) with synchronized RGB images, semantic segmentation, LiDAR point clouds, 2D bounding boxes, ego-vehicle states, and rich environment metadata.
- Designed for research in **object detection, segmentation, sensor fusion, imitation learning, and reinforcement learning**.
- Built on CARLA with varied weather, maps, and controllable traffic; packaged for **Hugging Face Datasets** with train/val/test splits and reproducible pipelines.

### CARLA Autopilot Images Dataset

[![Hugging Face](https://img.shields.io/badge/HuggingFace-dataset-yellow?style=for-the-badge&logo=huggingface)](https://huggingface.co/datasets/immanuel-peter/carla-autopilot-images)

- Open, multi-camera dataset (~188 GB, ≈68k frames) with synchronized RGB images, ego pose/velocity, control signals, traffic density, and collision logs.
- Collected in **CARLA** using synchronous stepping (Δt = 0.05 s), variable weather, and controllable NPC traffic; fixed extrinsics for front, front-left 45°, front-right 45°, and rear cameras.
- Packaged for **Hugging Face Datasets** with stable splits (56.2k/4.8k/7.2k) and a reproducible collection pipeline derived from **AutoMoE**. Suitable for imitation learning, vision-to-control, and sensor-fusion benchmarks.

### Semantic Image Search

[![GitHub Repo](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/immanuel-peter/semantic-image-search)

- Full-stack application for semantic image retrieval powered by **OpenAI’s CLIP model**.
- **Next.js** frontend (TypeScript & Tailwind CSS) provides a responsive interface for text-based search.
- **FastAPI** backend indexes images and computes CLIP embeddings to find and return similar images.

### LocalRAG – Terminal-based LLM with Infinite Memory

[![GitHub Repo](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/immanuel-peter/localrag)

- A terminal-based LLM chat tool with infinite memory through **FAISS-powered** local vector search.
- Designed to turn your terminal into a Claude/GPT-like chat interface with persistent, searchable memory.
- 100% local and privacy-respecting.

## Portfolio

Visit my digital homepage at [ipeter.dev](https://ipeter.dev) for my resume, academic progress, and evolving journey in AI, software engineering and entrepreneurship. You can also interact with **ImmanuelAI**, a chatbot that answers questions on my behalf.

## Contact Me

[![Outlook](https://img.shields.io/badge/Microsoft_Outlook-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white)](mailto:ipeter@uchicago.edu)
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/immanuel-peter/)
[![X](https://img.shields.io/badge/X-%23000000.svg?style=for-the-badge&logo=X&logoColor=white)](https://x.com/moby763canary21)
