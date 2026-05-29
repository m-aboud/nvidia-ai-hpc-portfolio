# Project Summary 

I built this portfolio to demonstrate hands-on familiarity with the NVIDIA AI infrastructure ecosystem. It includes a CUDA benchmark suite for CPU vs GPU performance testing, a Python capacity planner that converts GPU counts into rack, power, cooling, and PUE requirements, and a GPU observability stack using DCGM Exporter, Prometheus, and Grafana. My goal was to connect software-level GPU awareness with real production infrastructure requirements such as capacity, thermals, monitoring, and operational readiness.

This portfolio demonstrates practical AI/HPC infrastructure capability across three areas:

1. CUDA benchmarking and GPU performance awareness
2. AI cluster capacity planning for high-density GPU environments
3. NVIDIA GPU observability using DCGM Exporter, Prometheus, and Grafana

## 1. CUDA Benchmark Suite

A CUDA C++ benchmarking suite comparing CPU and GPU execution for common parallel workloads.

**Highlights:**

- Vector addition
- Matrix multiplication
- CUDA event timing
- CPU vs GPU comparison
- Reproducible build using Makefile and Docker

**Relevant to NVIDIA DevTech:**

- CUDA programming fundamentals
- Kernel launch configuration
- Memory allocation and transfer
- Performance measurement methodology

---

## 2. AI Cluster Capacity Planner

A Python CLI tool to estimate AI/HPC cluster infrastructure requirements.

**Highlights:**

- GPU count to rack count
- Power estimation
- Cooling tonnage
- PUE-adjusted facility load
- Example support for H100, H200, B200, GB200-style infrastructure planning

**Relevant to AI Infrastructure:**

- Data center planning
- GPU cluster design
- High-density rack sizing
- Power and cooling calculations
- Executive-friendly outputs

---

## 3. GPU Observability Platform

A Docker-based monitoring stack for NVIDIA GPU telemetry.

**Highlights:**

- NVIDIA DCGM Exporter
- Prometheus
- Grafana dashboard provisioning
- GPU utilization, memory, power, temperature, ECC, and health metrics

**Relevant to Production AI Platforms:**

- GPU fleet monitoring
- Incident detection
- Reliability engineering
- Observability and operations readiness
