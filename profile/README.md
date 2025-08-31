<div align="center">

<p>
  <img src="../logo/logo_light.png#gh-light-mode-only" alt="TinyLCM" width="140" />
  <img src="../logo/logo_dark.png#gh-dark-mode-only"  alt="TinyLCM" width="140" />
</p>

# TinyLCM — Tiny Life Cycle Management

**The on‑prem, edge‑first MLOps platform for tiny devices.**
*Less Ops, more ML at the edge · Assign once, deploy everywhere*

</div>

TinyLCM standardizes the **entire edge ML lifecycle** — data → training → deployment → monitoring → (re)training — for Raspberry‑class and MCU devices.

---

## 🎯 Vision & Mission

* **Vision:** A complete, open platform to run TinyML at fleet scale — reproducible (**DVC‑first**), secure (**TLS, RBAC, SHA256**), and cloud‑agnostic.
* **Mission:** Make edge ML *boringly reliable*: **Assignments** as the rollout truth, an edge agent with **MQTT + presigned S3**, **atomic switch & rollback**, and a data flow that anyone can reproduce.

## 🧭 What we’re building

* **Device & Fleet Management** · safe rollouts, rollback slots, telemetry.
* **Multi‑Tenant Projects** · clean isolation of use cases/teams.
* **Data Hub + Labeling** · curate inference data; export **DVC snapshots** for training.
* **Training Pipelines** · export code templates; track runs/metrics; CI‑friendly.
* **Model Registry & Runtime** · versioned models; manifest‑driven multi‑modal runners (vision, audio, time series, text, tabular).
* **Federated Learning** · on‑device rounds (head‑only/tiny‑full), optional secure aggregation.
* **Autonomous TinyML Apps** · **on‑device drift detection** and **auto‑retrain** via SDK (no cloud dependency).
* **Feature Storage** · edge feature cache + central Parquet/DuckDB exports.
