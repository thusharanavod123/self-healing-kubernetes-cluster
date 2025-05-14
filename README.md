# self-healin# Self-Healing Kubernetes Cluster

## Description
A Kubernetes cluster enhanced with AI-driven self-healing capabilities. This project uses Prometheus for monitoring and Python-based reinforcement learning agents to detect failures, predict issues, and automatically reschedule or restart pods/services for optimal uptime.

## Features
- Real-time cluster health monitoring with Prometheus
- Automated pod rescheduling and restarts
- Predictive failure detection using reinforcement learning
- Grafana dashboards for visualization

## Tech Stack
- Kubernetes
- Prometheus & Grafana
- Python (Reinforcement Learning: stable-baselines3 or similar)
- Docker

## Branches
- `main`: Stable, production-ready code
- `dev`: Active development
- `rl-agent`: Experimental reinforcement learning improvements
- `monitoring`: Monitoring and alerting enhancements

## Getting Started

1. **Clone the repository**
    ```
    git clone https://github.com/yourusername/self-healing-kubernetes-cluster.git
    cd self-healing-kubernetes-cluster
    ```

2. **Set up Kubernetes and Prometheus**
    - Follow the `docs/setup.md` for cluster and monitoring setup.

3. **Deploy the RL agent**
    ```
    kubectl apply -f k8s/rl-agent-deployment.yaml
    ```

4. **Monitor via Grafana**
    - Access dashboards as described in `docs/grafana.md`.

## License
MIT License
g-kubernetes-cluster
