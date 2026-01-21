# Metric Definition and Validation

Analytics platforms fail when metrics are ambiguous or unstable. This document defines a practical approach to metric governance and validation.

## Metric Definition Standard
Each metric specifies:
- Name and business meaning
- Source(s) of truth
- Calculation logic (including filters and edge cases)
- Grain (daily, campaign, account, etc.)
- Refresh SLA and latency expectations
- Owner (business) and steward (data)

## Validation Controls
- Completeness: expected coverage and null thresholds
- Consistency: cross-source reconciliation where applicable
- Reasonableness: range checks and anomaly detection
- Change impact: versioned definitions with effective dates

## Release Discipline
- No silent metric changes
- Backward compatibility where feasible
- Communication plan for changes impacting stakeholders
