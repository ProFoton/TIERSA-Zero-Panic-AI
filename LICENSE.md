# 🔒 END-USER LICENSE AGREEMENT (EULA)

## TIERSA™ TUNGSTEN CARBIDE v5.0

<p align="center">
  <b>Copyright © 2026. All rights reserved.</b><br>
  <b>Author & Chief Architect:</b> Evgeny Baydikov (ProFoton / TIERSA Sys)<br>
  <b>Corporate Contact:</b> <a href="mailto:dantesevg@gmail.com">dantesevg@gmail.com</a>
</p>

---

> [!IMPORTANT]
> **PLEASE READ THIS LICENSE AGREEMENT CAREFULLY BEFORE DOWNLOADING, INSTALLING, OR USING THE SOFTWARE.**
> 
> By downloading, installing, or running the pre-compiled binary file (**size: 1.17 MB**), you expressly and unconditionally agree to be bound by the terms of this proprietary End-User License Agreement (EULA). If you do not agree to these terms, you are **strictly prohibited** from using this software.

---

### 1. 📜 LICENSE GRANT AND LIMITATIONS
This Software is **licensed, not sold**. Based on a valid cryptographic license manifest (`*.key`) issued directly by the Author, you are granted:
* A **non-exclusive** and non-transferable right.
* A **fully limited** and temporary right to deploy the compiled binary file.
* Deployment exclusively within the **authorized network perimeter**.
* Operation strictly within the allocated capacity limits of the AI cluster (**restricted solely by the number of physical GPU/TPU units**).

### 2. 🚫 STRICT PROHIBITIONS AND COMMERCIAL PROTECTION
Under the terms of this EULA, the Licensee and any third parties are **strictly prohibited** from engaging in the following activities:

| Type of Prohibition | Description of Restriction |
| :--- | :--- |
| **No Slicing** *(Reverse Engineering)* | You may not reverse engineer, decompile, disassemble, modify, decrypt, or attempt to extract the source code or logical algorithm structures from the compiled binary file. |
| **Unauthorized Replication** | Copying, cloning, distributing, renting, sublicensing, hosting as a managed service (SaaS/PaaS), or otherwise commercially exploiting this software is strictly prohibited, regardless of any direct commercial contract with the Author. |
| **Bypassing Capacity Limits** | Any attempt to interfere with the built-in **RSA-PSS** cryptographic validation cycle or bypass the established limit on the number of allocated GPUs/TPUs will result in the **immediate and automatic revocation** of this license. |

### 3. 🛡️ DATA PRIVACY AND AIR-GAP MODE
The Software operates strictly within a **100% isolated local network perimeter** (Air-Gapped architecture). 

The Author guarantees that the Software:
* **Does not contain** hidden network telemetry modules.
* **Does not transmit** Large Language Model (LLM) weights externally.
* Functions in absolute compliance with sovereign data storage security protocols.

### 4. 🧠 INTELLECTUAL PROPERTY AND MONITORING
All titles, international copyrights, patents, trade secrets, and intellectual property rights within the Software remain the **sole and exclusive property of the Author**.

This includes, but is not limited to:
* Adaptive token pacing algorithms.
* Kalman filters for thermal zones.
* vLLM KV-cache management modules.

> [!NOTE]
> The production-grade metrics output via HTTP request is intended solely for real-time integration with the Licensee's **Prometheus / Grafana** monitoring systems.

### 5. ⚠️ DISCLAIMER OF WARRANTY ("AS IS")
THE SOFTWARE IS PROVIDED **"AS IS"**, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED.

The Author **shall not be held liable** for any physical or economic damage to the Licensee's hardware, including but not limited to:
* 💥 **VRM** power phase burnout.
* 🌡️ Thermal degradation of the **CoWoS** substrate.
* ❌ **HBM3e** memory failure crashes.
* 📉 Reduction of Mean Time Between Failures (**MTBF**).

*The Licensee assumes all risks associated with the operation of active power and thermal management controllers.*

### 6. ⏳ TERMINATION
This License terminates **automatically and immediately** without prior notice if:
1. You fail to comply with any provision of this agreement.
2. The validation key manifest assigned to you expires.

**Upon termination of the license, you must destroy all copies of the software binary file in your possession.**

---
<p align="center">
  <sub>TIERSA™ TUNGSTEN CARBIDE • 2026</sub>
</p>
