# MEDUSA Operational Modes

This document defines MEDUSA’s operational modes during mission execution.  
These modes describe how MEDUSA behaves in response to mission context, operator intent, and environmental conditions.

---

## 1. Standard Operational Mode
Description:
MEDUSA operates with full capability across ingestion, fusion, analytics, and behaviour modelling.

Characteristics:
- Full pipeline depth  
- High-fidelity fusion  
- Real-time analytics  
- Maximum confidence scoring  

Outcome:
Optimal mission performance.

---

## 2. High-Intensity Operational Mode
Description:
Activated during missions requiring rapid, continuous processing of large sensor volumes.

Characteristics:
- Parallel ingestion  
- Distributed fusion  
- High-throughput analytics  
- Prioritised operator outputs  

Outcome:
Sustained performance under heavy mission load.

---

## 3. Silent Mode
Description:
Used when MEDUSA must minimise network emissions or external signalling.

Characteristics:
- Local-only processing  
- No external API calls  
- Reduced telemetry  
- Offline analytics  

Outcome:
Operational discretion in sensitive environments.

---

## 4. Autonomous Mode
Description:
MEDUSA operates without operator oversight or external coordination.

Characteristics:
- Self-managed fallback logic  
- Local decision-making  
- Autonomous pipeline optimisation  
- Localised behaviour modelling  

Outcome:
Independent operation when external systems are unavailable.

---

## 5. GNSS-Denied Operational Mode
Description:
Activated when GPS/GNSS signals are unavailable or unreliable.

Characteristics:
- Alternative timestamp alignment  
- Confidence weighting adjustments  
- Partial-data fusion pathways  
- Behaviour modelling without positional anchors  

Outcome:
Operational continuity in contested environments.

---

## 6. Sensor-Degraded Operational Mode
Description:
Triggered when sensors fail, degrade, or produce corrupted data.

Characteristics:
- Dropout detection  
- Fusion rebalancing  
- Reduced pipeline depth  
- Confidence recalibration  

Outcome:
Stable analytics despite sensor loss.

---

## 7. Network-Degraded Operational Mode
Description:
Used when bandwidth is limited or intermittent.

Characteristics:
- Adaptive compression  
- Reduced feature vector size  
- Prioritised analytics outputs  
- Deferred non-critical processing  

Outcome:
Continued operation under network constraints.

---

## 8. Embedded Deterministic Mode
Description:
Used in embedded deployments with strict timing and resource constraints.

Characteristics:
- Deterministic execution paths  
- Fixed memory footprints  
- Minimal external dependencies  
- Predictable timing behaviour  

Outcome:
Reliable operation in constrained environments.

---

## Purpose
To provide DIU reviewers with a clear understanding of MEDUSA’s operational modes, demonstrating adaptability, mission readiness, and predictable behaviour across diverse environments.
