# Projects

This page provides the scope, current status, and next steps for the two featured projects in my cybersecurity portfolio.

---

## Sentinel X — Personal SIEM & Detection Engineering Project

**Status: Currently working on it**  
**Focus:** Security monitoring · Application log analysis · Detection engineering  
**Environment:** Wazuh on Ubuntu Server; related Flask web application

### Objective

Develop a practical SIEM lab that goes beyond a default dashboard by connecting application events to custom, testable security detections and clear investigation evidence.

### Current progress

- Wazuh dashboard is running in an Ubuntu Server virtual machine.
- Application/server log integration, custom detections, event correlation, and test validation remain in progress.

### Planned capabilities

1. **Application-aware log ingestion:** collect useful security events from the Flask application, including successful and failed authentication events where available.
2. **Custom parsing and detection:** create and test Wazuh decoders and rules for the application's event format.
3. **Repeated failed-login detection:** define a threshold for repeated authentication failures from the same source and alert on possible brute-force behaviour.
4. **Controlled validation:** test rules using representative log samples and controlled scenarios; compare expected results with actual alerts.
5. **Evidence and documentation:** record architecture, setup, rule logic, test cases, observed alerts, screenshots, and limitations.

### What makes it distinctive

The emphasis is on the complete detection path:

**Application event → log ingestion → custom rule → alert → validation evidence**

This demonstrates how detections are designed and tested, rather than only showing that a SIEM has been installed.

### Related repository

[SIEM-project-web-app](https://github.com/ArvindRaghav56/SIEM-project-web-app)

### Definition of done

The relevant feature will be marked complete only after it has been implemented, tested, and supported by reproducible evidence. No claim is made that the planned integrations or detections are already operational.

---

## Smart Emergency Alert System (SEAS)

**Status: Academic project documentation / prototype work**  
**Focus:** IoT concept · Emergency vehicle awareness · Location-based alerts

### Problem statement

Ambulances can be delayed when surrounding road users do not know that an emergency vehicle is approaching. SEAS explores a way to communicate that approach to nearby road users.

### Proposed solution

SEAS is an IoT-oriented concept in which an ambulance-side device and location/proximity information support an alert workflow for nearby vehicles. A simulated map/dashboard can demonstrate the idea without implying that a city-wide or production system has been deployed.

### Proposed components and technologies

- **Controller/platform:** NodeMCU ESP8266 or Raspberry Pi, depending on the prototype configuration
- **Location:** GPS module for ambulance position
- **Proximity awareness:** radar or ultrasonic sensing as explored in the hardware concept
- **Demonstration:** web-based map simulation showing ambulance movement and driver-side alerts
- **Integration concept:** hardware inputs and location data feeding the alert workflow

### Intended demonstration flow

1. Represent ambulance movement or position.
2. Detect or simulate an approaching emergency scenario.
3. Show an alert to a nearby road-user view.
4. Document the hardware/software architecture and the limitations of the prototype.

### Current portfolio evidence

The repository contains the [SEAS synopsis (PDF)](SEAS-synopsis-2.pdf), which documents the concept and proposed approach. It is not evidence of a production-ready system or of every proposed hardware component being fully integrated and tested.

---

## Implementation and reporting standards

For both projects, I aim to include clear architecture, reproducible setup steps, screenshots or logs where appropriate, test evidence, known limitations, and an honest distinction between completed features and planned work.

**Security hygiene:** Never publish credentials, API tokens, private IP addresses, or sensitive logs in public documentation.
