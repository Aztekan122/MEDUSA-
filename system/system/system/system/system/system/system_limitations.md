# MEDUSA System Limitations

This document defines the known limitations of the MEDUSA system.  
It ensures DIU reviewers understand the boundaries of MEDUSA’s performance, interoperability, and operational behaviour under specific conditions.

---

## 1. Sensor Limitations
- Fusion accuracy decreases when multiple sensors degrade simultaneously  
- Extremely low sampling rates reduce behavioural modelling fidelity  
- Non‑timestamped data cannot be fused without external alignment  
- Highly corrupted packets may be unrecoverable  

Outcome:  
Sensor quality directly affects fusion and analytics reliability.

---

## 2. Compute Limitations
- Real-time analytics may degrade on low-power edge hardware  
- Embedded deployments cannot support full pipeline depth  
- Distributed pipelines require synchronised clocks; drift reduces accuracy  
- Hardware acceleration is optional and not yet fully integrated  

Outcome:  
Compute constraints shape achievable performance.

---

## 3. Network Limitations
- High-throughput ingestion requires stable bandwidth  
- Distributed fusion suffers under intermittent connectivity  
- Network-degraded mode reduces feature vector richness  
- External system handshakes may fail under extreme latency  

Outcome:  
Network conditions directly influence operational modes.

---

## 4. Data Limitations
- Partial-data fusion reduces confidence scoring  
- Behaviour modelling accuracy decreases with missing metadata  
- Timestamp correction cannot fix non-monotonic sensor clocks  
- Legacy data formats may require lossy adaptation  

Outcome:  
Data integrity and completeness are critical for stable analytics.

---

## 5. Deployment Limitations
- Cloud deployments require container orchestration support  
- Edge deployments may lack redundancy for fault tolerance  
- Embedded deployments cannot support dynamic module replacement  
- Hybrid deployments require coordination logic not available in all environments  

Outcome:  
Deployment environment determines achievable capability.

---

## 6. Interoperability Limitations
- External systems must follow ICD versioning; mismatches reduce compatibility  
- Legacy adapters may reduce throughput or fidelity  
- API consumers must follow schema validation rules  
- Backward compatibility is guaranteed for one cycle only  

Outcome:  
Interoperability depends on strict adherence to ICD discipline.

---

## 7. Resilience Limitations
- GNSS-denial fallback reduces positional accuracy  
- Sensor dropout detection may fail under extreme noise  
- Confidence scoring degrades significantly under multi-sensor failure  
- Simulation-driven stress tests cannot cover all mission scenarios  

Outcome:  
Resilience mechanisms preserve functionality but reduce precision.

---

## 8. Security Limitations
- External interfaces require hardening; unprotected environments increase risk  
- Embedded deployments rely on secure boot; compromised hardware reduces assurance  
- Message integrity validation depends on external system compliance  
- API authentication requires stable key management  

Outcome:  
Security posture varies by deployment environment.

---

## Purpose
To provide DIU reviewers with a clear understanding of MEDUSA’s system limitations, demonstrating transparency, engineering discipline, and realistic operational expectations.
