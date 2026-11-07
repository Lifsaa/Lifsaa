# Salif Sanogo

I build distributed systems and ML infrastructure. CS at Cal Poly SLO (graduating December 2026), previously a software engineering intern at Amazon.

## Featured work

**[distributed-rl-scaling](https://github.com/Lifsaa/distributed-rl-scaling)**
PPO on Ray RLlib, run on a KubeRay cluster with 1 to 16 workers, to find where adding workers stops helping. Training time flattens past 8 workers because the centralized learner and cluster communication take over. Tuned hyperparameters nearly doubled best reward at 16 workers (99.5 to 198.3).
`Python` `Ray` `Kubernetes` `KubeRay` `Helm` `Optuna`

**[distributed-systems](https://github.com/Lifsaa/distributed-systems)**
Seven Go systems built in sequence: MapReduce over RPC, then across Docker containers, a sharded and replicated search engine, replicated banking with a fixed leader, and finally a five-node Raft-style cluster with leader election and log repair.
`Go` `gRPC` `Docker Compose` `SQLite` `Raft`

**[llm-agent-injection-benchmark](https://github.com/Lifsaa/llm-agent-injection-benchmark)**
A red-team benchmark for indirect prompt injection against a GPT-4o email agent with tools. Across 400 runs, combining Spotlighting and MELON-Aug cut attack success from 20% to 7%, at roughly twice the token cost.
`Python` `OpenAI tool calling` `pytest`

## Experience

**Amazon**, Software Development Engineer Intern (summer 2025). Moved a shipping-cost model from single-node LightGBM to distributed training on Ray, cutting training from 9 hours to under 2. Built AWS CDK infrastructure and CI/CD for ML training on SageMaker, and replaced Spark preprocessing with Polars.

## Tools I use most

Python, Go, C · Ray, Kubernetes, gRPC, Docker · AWS (SageMaker, CDK, EKS)

## Contact

[LinkedIn](https://www.linkedin.com/in/salif-sanogo-922593253) · sanogosalifpro@gmail.com
