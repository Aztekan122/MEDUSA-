# MEDUSA System Operational Modes

This document describes the operational modes MEDUSA supports across mission environments.  
It explains how the system adapts to sensor availability, compute constraints, network conditions, and degraded operational states.

---

## 1. Normal Mode
Description:
MEDUSA operates with full sensor availability, stable network conditions, and standard compute resources.

Capabilities:
- Full multi-sensor ingestion
- Complete feature extraction
- High-fidelity fusion
- Real-time analytics
- Maximum confidence scoring

Outcome:
Optimal performance with full system capability.

---

## 2. High-Throughput Mode
Description:
Used in cloud or data-center environments where compute and bandwidth are abundant.

Capabilities:
- Parallel ingestion pipelines
- Distributed fusion across nodes
- Batch analytics for large datasets
- High-volume mission replay

Outcome:
Maximum scalability and throughput.

---

## 3. Low-Latency Edge Mode
Description:
Used in edge deployments where latency is critical and compute is moderate.

Capabilities:
- Reduced pipeline depth
- Localised fusion
- Lightweight analytics
- Rapid confidence scoring

Outcome:
Fast response times with mission-relevant accuracy.

---

## 4. Embedded Deterministic Mode
Description:
Used in embedded hardware with strict timing and resource constraints.

Capabilities:
- Deterministic execution paths
- Fixed memory footprints
- Hardware-accelerated analytics (future roadmap)
- Minimal external dependencies

Outcome:
Predictable behaviour under constrained environments.

---

## 5. GNSS-Denied Mode
Description:
Activated when GPS/GNSS signals are unavailable or unreliable.

Capabilities:
- Alternative timestamp alignment
- Confidence weighting for degraded inputs
- Partial-data fusion pathways
- Behaviour modelling without positional anchors

Outcome:
Operational continuity in contested environments.

---

## 6. Sensor-Degraded Mode
Description:
Triggered when one or more sensors fail, degrade, or produce corrupted data.

Capabilities:
- Dropout detection
- Autonomous fallback pathways
- Fusion rebalancing
- Confidence recalibration

Outcome:
Stable analytics despite sensor loss.

---

## 7. Network-Degraded Mode
Description:
Used when bandwidth is limited or intermittent.

Capabilities:
- Adaptive compression
- Reduced feature vector size
- Prioritised analytics outputs
- Deferred non-critical processing

Outcome:
Continued operation under network constraints.

---

## 8. Autonomous Mode
Description:
MEDUSA operates without external coordination or oversight.

Capabilities:
- Local decision-making
- Self-managed fallback logic
- Autonomous pipeline optimisation
- Localised behaviour modelling

Outcome:
Independent operation when external systems are unavailable.

---

## Purpose
To provide DIU reviewers with a clear understanding of MEDUSA’s operational modes, demonstrating adaptability, resilience, and mission readiness across diverse environments.
