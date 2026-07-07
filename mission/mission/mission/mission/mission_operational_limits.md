# MEDUSA Mission Operational Limits

This document defines the operational limits under which MEDUSA is designed to function during real-world defence missions.  
It ensures DIU reviewers understand the boundaries of MEDUSA’s mission behaviour, including environmental, computational, temporal, and sensor-related limits.

---

## 1. Environmental Limits
- **Maximum acoustic noise tolerance:** Up to extreme battlefield noise levels before feature extraction degrades  
- **Maximum RF interference tolerance:** Up to defined EMI thresholds before signal classification becomes unreliable  
- **Weather tolerance:** Sensors must remain within manufacturer-defined operational ranges  
- **GNSS-denial duration:** Unlimited, but positional accuracy decreases over time without alternative alignment sources  

Outcome:  
MEDUSA remains stable within measurable environmental boundaries.

---

## 2. Sensor Limits
- **Sampling rate variability:** Fusion remains stable within ±20% of nominal sensor rates  
- **Metadata loss tolerance:** Up to 30% missing metadata before behaviour modelling degrades  
- **Legacy sensor throughput:** Limited by adapter normalization capacity  
- **Non-monotonic timestamp correction:** Effective up to defined temporal drift thresholds  

Outcome:  
Fusion and analytics remain reliable within sensor variability limits.

---

## 3. Network Limits
- **Minimum bandwidth for essential analytics:** Low-bandwidth fallback supports critical outputs  
- **Maximum tolerable latency:** Up to mission-defined thresholds before operator dashboards degrade  
- **Network partition duration:** Unlimited, but cloud analytics unavailable until reconnection  
- **External system delay tolerance:** Up to defined ICD timing limits  

Outcome:  
Mission continuity persists under constrained connectivity.

---

## 4. Compute Limits
- **Minimum compute for reduced-depth pipeline:** Edge devices must meet baseline CPU/GPU thresholds  
- **Embedded deterministic timing:** Execution must remain within fixed timing windows  
- **Cloud scaling limits:** Dependent on deployment configuration  
- **Power constraint tolerance:** Reduced-depth pipeline activates under low-power conditions  

Outcome:  
MEDUSA adapts pipeline depth based on compute availability.

---

## 5. Operator Limits
- **Maximum alert frequency:** Alerts are rate-limited to prevent operator overload  
- **Override safety boundaries:** Unsafe overrides are rejected  
- **Dashboard update latency:** Must remain within mission tolerances  
- **Replay interaction limits:** Replay fidelity depends on available datasets  

Outcome:  
Operator interaction remains safe and predictable.

---

## 6. External System Limits
- **ICD version compatibility:** Only supported ICD versions guarantee correct integration  
- **Schema compliance:** Export formats must match defined schemas  
- **Timing constraints:** External systems must respond within mission-defined windows  
- **Data completeness:** External systems must provide minimally structured data  

Outcome:  
Integration remains stable within defined external boundaries.

---

## 7. Mission Timeline Limits
- **Real-time analytics latency:** Must remain within mission tolerances  
- **Fusion update frequency:** Limited by sensor sampling rates  
- **Behaviour model refresh rate:** Must remain within mission-defined intervals  
- **Replay dataset completeness:** Limited by ingestion and logging fidelity  

Outcome:  
Time-sensitive mission behaviour remains predictable.

---

## Purpose
To provide DIU reviewers with a clear understanding of MEDUSA’s operational limits, demonstrating disciplined engineering and realistic mission boundaries.
