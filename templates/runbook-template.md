# Runbook template

Copy this into your repo for each critical system.

## System
Name:
Owner (you):
Purpose:

## Dependencies
- service-a
- service-b
- database
- object storage
- third-party auth

## Normal behavior
- Key endpoints/flows:
- Expected latency:
- Expected error rate:

## Dashboards / logs
- Where to look first:
- Common filters/queries:

## Alerts
- What triggers paging:
- What is noise:

## Known failure modes
1) Symptom:
   Likely cause:
   Mitigation:
2) Symptom:
   Likely cause:
   Mitigation:

## Kill switches
- Feature flag:
- Maintenance mode:
- Rate limit multiplier:

## Recovery steps (when it’s broken)
1) Confirm impact
2) Apply mitigation
3) Verify recovery
4) Leave notes
