# High-Performance Memory Management Research (C++)

## 📑 Overview
This repository contains a technical investigation into Low-Level Memory Management and its impact on algorithmic performance. The core objective is to develop and benchmark specialized Memory Allocators (Pool, Stack, and Slab) to minimize latency and fragmentation in high-frequency trading or real-time systems.

<!-- This research is currently being documented for submission to the QuantUNAB Journal (National University of Barranca). -->

## 🔬 Research Goals
1. Complexity Analysis: Implementing custom allocators with $O(1)$ time complexity for allocation and deallocation.
2. Performance Benchmarking: Comparative analysis against standard library heap management (std::malloc/new).
3. Hardware Interaction: Optimizing data locality and cache hit rates through contiguous memory layouts.

## 🏗️ Project Structure (In-Progress)
- include/: Header-only implementations (Templates).
- src/: Main entry point and benchmark drivers.
- benchmarks/: Data collection scripts and performance metrics.
<!-- - docs/: Research paper drafts (APA 7th Ed.). -->

## 🛠️ Current Development
Currently implementing the Pool Allocator module using the Free List pattern.

### Roadmap 2026
- [ ] Phase 1 (March/April): Pool Allocator implementation & Benchmarking.
- [ ] Phase 2 (May): Publication in QuantUNAB.
- [ ] Phase 3 (June/July): Microkernel memory integration.

## 👨‍🔬 Researcher
Rafael Elias Arriaga Mendoza Systems Engineering Student | High-Performance Computing Enthusiast [ORCID Profile](https://orcid.org/0009-0004-1628-4674) | [LinkedIn](https://linkedin.com/in/reamdev)
