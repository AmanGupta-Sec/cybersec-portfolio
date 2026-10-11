# Project index

This folder contains project documentation and summaries.

## Sentinel X — Personal SIEM & Detection Engineering Project

**Status: In progress · Personal project.**

Sentinel X is my personal Wazuh-based security monitoring project. Its goal is to go beyond a default dashboard and demonstrate a practical detection pipeline for a web application.

### Current baseline
- Wazuh dashboard running in an Ubuntu Server virtual machine.

### Planned differentiating features

1. **Application-aware log ingestion:** collect structured events from the Flask application, such as successful logins, failed logins, and user activity.
2. **Custom Wazuh decoder and rules:** parse the application's event format and create detections specific to these events.
3. **Repeated-failure correlation:** identify multiple failed logins from one source IP as a possible brute-force pattern, with an elevated alert severity.
4. **Rule testing and validation:** use Wazuh's log-testing workflow and controlled test cases to check whether each rule triggers as expected.
5. **End-to-end evidence:** document the flow from application event to SIEM alert, including test inputs, expected results, observed alerts, screenshots, and limitations.

### Why this is more than a basic SIEM demo
The emphasis is on creating and validating application-specific detections and explaining why an event becomes an alert—not merely installing Wazuh or showing its dashboard.

The related web application repository is [SIEM-project-web-app](https://github.com/ArvindRaghav56/SIEM-project-web-app).

**Implementation status:** The Wazuh dashboard is the current baseline. The application-log integration, custom detection rules, correlation, and validation evidence above are planned and should be marked complete only after they have been implemented and tested.

**Security hygiene:** Do not publish dashboard credentials, tokens, private IPs, or sensitive logs in screenshots or documentation.

## Smart Emergency Alert System (SEAS)

The [SEAS synopsis](SEAS-synopsis-2.pdf) documents the academic project concept and proposed approach. This file is project documentation; it should not be interpreted as proof that a production-ready system has been deployed.
