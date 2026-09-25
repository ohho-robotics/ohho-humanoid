# OhhO Humanoid 🤖

The bipedal reference architecture for OhhO OS. Demonstrates full-body whole-body control (WBC) and dual-arm mobile manipulation using SmolVLA.

This repository is part of the **[OhhO Robotics Platform](https://github.com/ohho-robotics)**. It acts as the meta-workspace for onboarding this specific form factor into the OhhO ecosystem.

## 🚀 Quick Start (Simulation)
You can test the AI models and control stack for this robot in the OhhO Digital Twin without physical hardware.

```bash
git clone https://github.com/ohho-robotics/OhhO-Humanoid.git
cd OhhO-Humanoid
vcs import src < ohho.repos
docker compose up -d
```

## 🧩 OhhO Integration
This hardware profile natively supports:
- **OhhO Fleet**: Live telemetry and multi-agent coordination.
- **OhhO Connect**: ROSBridge / WebRTC low-latency streaming.
- **OhhO Mind**: VLA-based spatial intelligence.
