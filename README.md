# ZK-Paper-Zoo

This repository collects **practical, non-theoretical applications of zero-knowledge proofs (ZKPs)** featured in top-tier computer systems and security conferences and journals (e.g., S&P, USENIX Security, CCS, NDSS, OSDI, SOSP, PLDI, ASPLOS, EuroSys, etc.).  

The focus is on **real-world system designs, implementations, and use cases**—not cryptographic theory, proof system constructions, or complexity analysis. Each entry includes a brief summary highlighting the problem addressed, ZK technique used, and practical impact.

---

## 📄 Paper List

### System

* [Asplos26] [Evaluating Compiler OptimizationImpacts on zkVM Performance]().
* [Asplos23] [GZKP: A GPU Accelerated Zero-Knowledge Proof System]().

### PL

* [AsiaCCS] [Sok: Understanding ZkVM: From Reaserach to Practice]().
* [PLDI24] [Automated Detection of Under-constrained Circuits in Zero-Knowledge Proofs]().

### Security

* [NDSS25] [MTZK: Testing and Exploring Bugs in Zero-Knowledge (ZK) Compilers]().
* [sp24] [Certifying Zero-Knowledge Circuits with Refinement Types]().
* [sec26] [Arguzz: Testing zkVMs for Soundness and Completeness Bugs]().
* [Sec24] [SoK: Understanding zk-SNARKs: The Gap Between Research and Practice]().
* [Sec24] [Practical Security Analysis of Zero-Knowledge Proof Circuits]().
* [Sec24] [ZKSMT: A VM for Proving SMT Theorems in Zero Knowledge]().
* [CCS24] [fAmulet: Finding Finalization Failure Bugs in Polygon zkRollup]().
* [CCS24] [zkLogin: Privacy-Preserving Blockchain Authentication with Existing Credentials]().

### Software Engineer

* [ASE25] [ScaleCirc: Scaling the Analysis over Circom Circuits]().
* [ICSE2025] [ConsCS: Effective and Efficient Verification of Circom Circuits]().

### Measurement

* [WWW23] [On How Zero-Knowledge Proof Blockchain Mixers Improve, and Worsen User Privacy]().

---

> **Note**: This list emphasizes papers where ZKPs serve as an *enabling tool for system functionality*, not the core cryptographic contribution. Theoretical advances (e.g., new SNARKs, MPC-in-the-head variants) are excluded unless they include a compelling systems evaluation or deployment.
