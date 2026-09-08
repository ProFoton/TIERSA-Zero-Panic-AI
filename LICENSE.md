# 🔒 END-USER LICENSE AGREEMENT (EULA)

## TIERSA™-Zero-Panic-AI™ (v5.0 Tungsten Carbide)

<p align="center">
  <b>Copyright © 2026 Evgeny Baydikov. All rights reserved.</b><br>
  <b>Proprietor, Author & Chief Architect:</b> Evgeny Baydikov (ProFoton / TIERSA Sys)<br>
  <b>Corporate Contact:</b> <a href="mailto:dantesevg@gmail.com">dantesevg@gmail.com</a>
</p>

---

> [!IMPORTANT]
> **PLEASE READ THIS END-USER LICENSE AGREEMENT ("EULA") CAREFULLY BEFORE DOWNLOADING, INSTALLING, OR OPERATING THE SOFTWARE.**
> 
> By downloading, installing, or executing the pre-compiled binary file (**size: 1.17 MB**), you expressly, explicitly, and unconditionally agree to be bound by the terms of this proprietary license. If you do not agree to these terms, you are **strictly prohibited** from using this software.

---

### 1. ⚖️ LEGAL ANCHORING, OWNERSHIP, AND BRAND EVOLUTION

* **Sole Proprietorship:** This Software, including all its variations, compiled binaries, algorithms, and documentation, is the exclusive intellectual property of the individual physical person **Evgeny Baydikov** (hereinafter referred to as the **"Author"** / **"Rightsholder"**).
* **Commercial Nomenclature:** The Author operates under the commercial trade names **TIERSA™**, **TIERSA™-Zero-Panic-AI™**, and **TIERSA Sys**. Any reference to these entities in this document, the source code, binary metadata, network headers, or telemetry metrics implies direct and indivisible assignment of rights to **Evgeny Baydikov**.
* **Corporate Succession Clause:** In the event that the Author establishes, registers, or incorporates a dedicated corporate legal entity (e.g., *TIERSA Inc.*, *TIERSA LLC*, or *TIERSA Ltd.*), all titles, copyrights, and intellectual property vectors mentioned herein shall seamlessly transition to said legal entity without requiring modification of the compiled binary structures or historical license manifests.

### 2. 📜 LICENSE GRANT AND IMMUTABLE LIMITATIONS
This Software is **licensed, not sold**. Based on a valid cryptographic license manifest (`*.key`) issued directly and signed by the Author, the Licensee is granted:
* A **non-exclusive**, non-transferable, revocable, and temporary right to deploy the compiled binary file.
* Deployment rights exclusively within the **authorized isolated network perimeter** (Air-Gapped environment).
* Operation strictly capped by the hardcoded capacity limits of the AI cluster (**restricted by the specific number of physical GPU/TPU units** designated in the `.key` manifest).

### 3. 🚫 STRICT PROHIBITIONS AND REVERSE-ENGINEERING BARRIERS

| Type of Violation | Legal & Technical Restriction |
| :--- | :--- |
| **No Slicing** *(Reverse Engineering)* | You are strictly prohibited from reverse engineering, decompiling, disassembling, modifying, decrypting, or attempting to extract the source code, intermediate representations, or logical algorithm structures from the compiled binary file. |
| **Tampering with Identity Metadata** | Any attempt to strip, alter, patch, or obfuscate hex-strings, headers, or environment variables containing the strings `Evgeny Baydikov`, `TIERSA`, or `TIERSA-Zero-Panic-AI` within the binary file is a direct violation of copyright law and triggers immediate termination. |
| **Unauthorized Replication** | Copying, cloning, distributing, renting, sublicensing, or hosting this software as a managed service (SaaS/PaaS) is strictly prohibited, regardless of any external cloud orchestration layers. |
| **Bypassing Capacity Limits** | Any attempt to bypass the built-in **RSA-PSS** cryptographic validation cycle or forge the capacity metric limits will result in **immediate and automatic revocation** of this license. |

### 4. 🧠 INTELLECTUAL PROPERTY AND METRIC SIGNATURES
All titles, international copyrights, patents, trade secrets, and intellectual property rights within the Software remain the **sole and exclusive property of Evgeny Baydikov**. 

This protection encompasses, but is not limited to:
* Adaptive token pacing and micro-pacing algorithms.
* Kalman filters tailored for accelerator thermal zones.
* vLLM-Native PagedAttention memory swapping architectures.

> [!NOTE]
> All production-grade metrics outputted via HTTP request for **Prometheus / Grafana** monitoring are natively stamped with an immutable cryptographic signature string (`# tiersa_signature: signed_by_evgeny_baydikov`) generated at runtime.

### 5. ⚠️ FULL DISCLAIMER OF WARRANTY ("AS IS")
THE SOFTWARE IS PROVIDED **"AS IS"**, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE.

Under no circumstances shall the Author (**Evgeny Baydikov**) or **TIERSA™-Zero-Panic-AI™** be held liable for any physical, structural, or economic damage to the Licensee's hardware or infrastructure, including but not limited to:
* 💥 **VRM** power phase burnout or electrical overstress.
* 🌡️ Thermal degradation of the **CoWoS** substrate.
* ❌ **HBM3e** or high-bandwidth memory failure crashes under heavy transient loads ($di/dt$).
* 📉 Premature reduction of Mean Time Between Failures (**MTBF**).

*The Licensee assumes all operational risks associated with real-time hardware thermal mitigation.*

### 6. ⏳ TERMINATION AND LIQUIDATION
This License terminates **automatically, instantly, and without prior notice** from the Author if:
1. The Licensee fails to comply with any single provision of this EULA.
2. The cryptographic validation key manifest (`*.key`) assigned to the cluster expires.

**Upon termination, the Licensee is legally obligated to immediately cease all operations of the software and completely destroy all copies, binaries, and mirrors of the executable file in their possession.**

---
<p align="center">
  <sub>TIERSA™-Zero-Panic-AI™ • Copyright © 2026 Evgeny Baydikov</sub>
</p>
