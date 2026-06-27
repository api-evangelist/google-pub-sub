---
title: "Scaling Ray Serve LLM on GKE: Performance without losing the developer experience"
url: "https://cloud.google.com/blog/products/containers-kubernetes/improving-ray-serve-llm-on-gke-throughput-latency/"
date: "2026-06-18"
feed_url: "https://cloudblog.withgoogle.com/rss/"
---
Through collaboration with Anyscale, Google introduced three architectural optimizations to Ray Serve LLM on Kubernetes: HAProxy integration for request routing, direct token streaming, and an updated Ray executor backend for vLLM, delivering up to 5x higher throughput and 8x lower latency. The improvements were benchmarked on GKE clusters using NVIDIA HGX B200 systems running Gemma 4 E2B, with developers encouraged to try Ray 2.56 and later.
