# Microsoft Sentinel SIEM Project

## Objective
[Brief Objective - Remove this afterwards]

The Microsoft Sentinel SIEM project focused on deploying and configuring a cloud based SIEM to simulate real world Security Operations Center monitoring and detection activities. The objective was to ingest security telemetry from multiple sources, analyze logs using Kusto Query Language, generate actionable alerts, and perform Tier 1 SOC style investigations to identify and respond to suspicious activity.

This project was designed to demonstrate practical experience with SIEM implementation, log analysis, alert triage, and incident response using Microsoft Sentinel in an enterprise like environment.

### Skills Learned


- Practical implementation and operation of Microsoft Sentinel as a SIEM platform.
- Log ingestion and normalization using Azure Log Analytics.
- Writing and tuning KQL queries to detect suspicious authentication and security events.
- Alert triage and incident investigation following SOC Tier 1 workflows.
- Correlation of identity, security, and activity logs to identify potential threats.
- Documentation and communication of investigation findings.
- Understanding of cloud based security monitoring and identity focused detections.

### Tools Used
[Bullet Points - Remove this afterwards]

- Microsoft Sentinel for SIEM monitoring, detection, and incident management.
- Azure Log Analytics Workspace for centralized log storage and querying.
- Azure Active Directory logs for identity and authentication monitoring.
- Microsoft Defender data sources for security telemetry.
- Kusto Query Language for log analysis and detection logic.
- Azure Portal for configuration and management.

## Steps
Ref 1: Sentinel Deployment and Architecture
Set up Microsoft Sentinel in an Azure Log Analytics workspace. Designed workspace architecture, enabled required permissions, and ensured connectivity across security telemetry sources.

Ref 2: Data Connector Configuration
Configured multiple data connectors including Azure AD sign in logs, Defender for Cloud data, and Windows Security Event logs to funnel telemetry into Sentinel for analysis. Verified successful ingestion across log tables.

Ref 3: Log Normalization and Query Building
Utilized KQL to analyze ingested data, identify failed sign in attempts, unusual network activity, and other anomalies. Built custom detection queries based on SIEM best practices.

Ref 4: Analytics Rule Creation and Tuning
Created custom analytics rules in Sentinel to generate alerts from suspicious activity patterns. Tuned rule thresholds to balance detection coverage and false positive reduction.

Ref 5: Incident Generation and Alert Triage
Evaluated generated alerts within Sentinel, blazed incident records, and performed alert triage. Documented initial context, correlated multiple signals, and classified severity.

Ref 6: Investigation and Response Documentation
Investigated alerts using Sentinel’s investigation tools, entity relationships, and correlated logs. Recorded findings, response steps, and resolution activities following SOC documentation standards.

Ref 7: Workbooks and Dashboards
Created workbooks for visualizing log patterns, alert trends, and key security metrics. Used workbooks as operational tools to monitor ongoing SOC telemetry.
