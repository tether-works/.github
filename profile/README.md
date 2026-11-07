# tetherWorks

**Independent Systems Engineering, Spatial Computing & Autonomous Software Studio.**

We build native, zero-bloat systems tools, deterministic hardware simulation harnesses, high-frame-rate XR environments, and multi-agent software factories.

---

### Core Engineering Pillars

- **Low-Level Systems & Hardware Interop** — Native Windows/Linux systems architecture (.NET 10, C++, Rust), Win32 DeviceIoControl, raw SCSI MMC-5 pass-through, MTA COM interop, and custom binary file systems (ISO 9660, Joliet, UDF 1.02, El Torito, PAR2).
- **Simulation-First & Autonomous Agent Engineering** — Designing deterministic in-memory protocol and hardware simulators (VirtualDiscBackend) paired with multi-node agent coordinators and local Vision-Language Models (Qwen VLM) for zero-human-babysitting verification.
- **Spatial Computing & High-Refresh XR** — Standalone (Quest 3) and PCVR (OpenXR) simulation, 90/120 Hz frame-budget engineering, custom shader/PBR pipelines, and automated spatial VLM playtesting.
- **Algorithmic Audio & DSP** — Sample-accurate Red Book audio mastering, hardware C2 error-pointer recovery, AccurateRip verification, and spectral/timbre-locked generative soundtrack pipelines.

---

### Shipped Flagship Projects

- **[IgnisDisc Optical Studio](https://ignisdisc.tetherworks.dev)** ([	ether-works/IgnisDisc](https://github.com/tether-works/IgnisDisc)) — Native Windows 10/11 CD, DVD & Blu-ray burning, C2/AccurateRip audio ripping, and multi-disc PAR2 archival studio built on .NET 10, Windows IMAPIv2 COM, and direct SCSI MMC-5 pass-through. Verified by 481 automated tests against an in-memory virtual optical drive simulator.