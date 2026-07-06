# MEDUSA Operational Envelopes

This document defines the operational envelopes within which MEDUSA is designed to function.  
It provides DIU reviewers with clarity on environmental, computational, and mission-specific operating conditions.

## 1. Environmental Envelope
MEDUSA is designed to operate under:
- GNSS-denied conditions
- Variable sensor availability
- High-noise environments
- Intermittent connectivity
- Harsh physical conditions (platform-dependent)

Limits:
- Extreme sensor degradation may reduce fusion accuracy
- Severe bandwidth constraints may limit analytics throughput

## 2. Computational Envelope
Supported compute environments:
- Cloud (high compute, scalable)
- Edge (moderate compute, low latency)
- Embedded (constrained compute, deterministic)

Limits:
- Embedded deployments may require reduced model complexity
- Edge deployments may require pipeline simplification

## 3. Temporal Envelope
MEDUSA supports:
- Real-time processing
- Near-real-time analytics
- Batch-mode analysis (cloud)

Limits:
- Ultra-low-latency missions may require specialised hardware
- High-frequency sensor streams may require pipeline tuning

## 4. Mission Envelope
MEDUSA is suitable for:
- Multi-sensor fusion missions
- GNSS-denied navigation support
- Behaviour modelling and detection
- Tactical decision-support
- Autonomous system augmentation

Limits:
- Mission-specific ICDs may restrict output formats
- Legacy system integration may require adapter modules

## 5. Data Envelope
MEDUSA can operate with:
- Raw sensor data
- Synthetic simulation data
- Partial or degraded inputs
- Multi-modal streams

Limits:
- Completely missing sensor classes may reduce analytics fidelity
- Highly inconsistent timestamps may require preprocessing correction

## Purpose
To give DIU reviewers a clear understanding of the operational conditions MEDUSA is designed to support, and the boundaries within which it performs reliably.
