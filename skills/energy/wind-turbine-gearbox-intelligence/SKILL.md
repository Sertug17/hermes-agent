\# Wind Turbine Gearbox Maintenance Intelligence



\## Purpose



This skill evaluates gearbox condition in wind turbines based on:



\- Visual inspection findings (borescope)

\- Oil analysis (iron ppm levels)

\- Vibration status

\- Temperature anomalies



It provides a structured maintenance decision output.



---



\## Supported Turbine Models



\- Sinovel SL1500 (initial support)

\- Extendable to other platforms



---



\## Fault Modes Covered



\- Main bearing pitting

\- Spalling

\- Surface fatigue

\- Lubrication degradation indicators



---



\## Severity Index Scale



1 – Cosmetic

2 – Minor wear (monitor)

3 – Controlled monitoring required

4 – High failure probability (short-term intervention)

5 – Immediate shutdown required



The presence of confirmed pitting enforces a minimum severity of 3, even if vibration remains within normal range.



---



\## Oil Iron (Fe ppm) Classification



< 40 ppm → Normal

40–80 ppm → Elevated

80–120 ppm → High

> 120 ppm → Critical  



---



\## Decision Logic



The agent evaluates:



1\. Visual damage presence

2\. Oil iron classification

3\. Vibration presence



It then outputs:



\- Root cause assessment

\- Severity index

\- Shutdown recommendation

\- Monitoring interval

\- Escalation triggers



---



\## Example Case (Sinovel SL1500)



Input:

\- Main bearing rotor side pitting

\- No vibration anomaly

\- Oil Fe = 54 ppm



\### Output



Root Cause:

Localized early-stage surface fatigue



Severity Index:

3 / 5



Immediate Shutdown Required:

No



Monitoring Strategy:

Quarterly inspection (3 months)



Escalation Triggers:



\- Fe exceeds 80 ppm

\- Onset of axial or radial vibration

\- Temperature drift above baseline



\## Intended Use



This skill is designed for condition-based maintenance support.

It does not replace engineering judgment or OEM recommendations.



