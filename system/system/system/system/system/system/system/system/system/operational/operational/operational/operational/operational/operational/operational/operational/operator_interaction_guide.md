# MEDUSA Operator Interaction Guide

This document describes how operators interact with MEDUSA across mission phases, interfaces, and deployment environments.  
It ensures DIU reviewers understand MEDUSA’s usability, operator workflows, and interaction patterns.

---

## 1. Operator Roles
MEDUSA supports three primary operator roles:

### Mission Analyst
- Interprets fused outputs  
- Reviews analytics and behaviour models  
- Monitors confidence scoring  
- Initiates mission replay  

### System Integrator
- Manages ICD alignment  
- Configures external interfaces  
- Oversees deployment model selection  
- Validates schema compliance  

### Field Operator
- Runs edge or embedded deployments  
- Monitors degraded-mode indicators  
- Executes manual overrides when authorised  
- Ensures sensor connectivity  

Outcome:  
Clear role separation ensures predictable system interaction.

---

## 2. Operator Interfaces
Operators interact with MEDUSA through:

### Dashboard Interface
- Real-time fused outputs  
- Analytics visualisation  
- Confidence scoring indicators  
- Degraded-mode alerts  

### API Endpoints
- Programmatic ingestion  
- External system integration  
- Schema-validated message exchange  

### ICD Message Streams
- Structured communication with external systems  
- Versioned schema enforcement  
- Legacy adapter compatibility  

### Mission Replay Tools
- Timeline navigation  
- Sensor reconstruction  
- Behaviour analysis  

### Configuration Profiles
- Pre-mission setup  
- Deployment model selection  
- Pipeline tuning  

Outcome:  
Multiple interfaces support diverse mission roles.

---

## 3. Interaction During Mission Phases

### Pre-Mission
- Configure sensors  
- Validate ICD alignment  
- Select deployment model  
- Review configuration profiles  

### Active Mission
- Monitor fused outputs  
- Review analytics  
- Respond to degraded-mode alerts  
- Execute authorised overrides  

### Post-Mission
- Run mission replay  
- Export fused and analytic outputs  
- Evaluate performance  
- Update configuration profiles  

Outcome:  
Operators follow structured workflows across mission phases.

---

## 4. Degraded-Mode Interaction
Operators receive clear indicators when MEDUSA enters degraded modes:

- Sensor dropout alerts  
- Network degradation warnings  
- GNSS-denial notifications  
- Reduced pipeline depth indicators  

Operators may:
- Adjust mission parameters  
- Trigger manual overrides  
- Switch deployment models  
- Review confidence scoring changes  

Outcome:  
Predictable operator behaviour under mission stress.

---

## 5. Manual Override Procedures
Manual overrides are restricted and require:

- Mission analyst approval  
- Clear justification  
- Awareness of pipeline impact  
- Post-override validation  

Overrides may:
- Force pipeline depth changes  
- Switch operational modes  
- Adjust fusion weighting  
- Trigger fallback pathways  

Outcome:  
Controlled operator intervention.

---

## 6. Operator Safety & Security Practices
Operators must ensure:

- API authentication is active  
- Message integrity validation is enabled  
- External interfaces are hardened  
- Embedded deployments use secure boot  

Outcome:  
Consistent operational security posture.

---

## Purpose
To provide DIU reviewers with a clear understanding of how operators interact with MEDUSA, demonstrating usability, mission readiness, and disciplined operational engineering.
