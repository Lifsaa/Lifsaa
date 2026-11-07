# Hey, I'm Salif

CS student at Cal Poly SLO, graduating December 2026. I'm into distributed systems and ML infra: getting training jobs to run across a lot of machines, and figuring out where adding more machines stops paying off. I worked on exactly that as an SDE intern at Amazon last summer.

## Projects

### [distributed-rl-scaling](https://github.com/Lifsaa/distributed-rl-scaling)

I trained a PPO agent with Ray RLlib on a Kubernetes cluster (KubeRay), using 1 to 16 workers, to see how much faster it actually gets. Past 8 workers it barely improved, because the central learner and network traffic become the bottleneck. Tuning hyperparameters took best reward at 16 workers from 99.5 to 198.3.

Python · Ray · Kubernetes · KubeRay · Helm · Optuna

### [distributed-systems](https://github.com/Lifsaa/distributed-systems)

Seven Go projects from my distributed systems class, each one building on the last. It starts with MapReduce over RPC and ends with a five-node Raft-style cluster that elects a leader and repairs follower logs. In between there's a sharded, replicated search engine.

Go · gRPC · Docker Compose · SQLite

### [llm-agent-injection-benchmark](https://github.com/Lifsaa/llm-agent-injection-benchmark)

Can a malicious email trick a GPT-4o email agent into sending, deleting, or forwarding mail? Over 400 runs with no defense, 20% of attacks worked. Stacking Spotlighting and MELON-Aug brought that down to 7%, at about twice the token cost.

Python · OpenAI tool calling · pytest

## Amazon, SDE intern (summer 2025)

I moved a shipping-cost model from single-node LightGBM to distributed training on Ray, which cut training time from 9 hours to under 2. I also set up the AWS CDK infrastructure and CI/CD for ML training on SageMaker, and swapped the Spark preprocessing for Polars.

## Contact

[LinkedIn](https://www.linkedin.com/in/salif-sanogo-922593253) · sanogosalifpro@gmail.com
