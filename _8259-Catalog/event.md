---
layout: default
title: Cybersecurity Event Awareness
navOrder: 6
navTitle: Event
permalink: /event/
---

# Cybersecurity Event Awareness

## Access to Event Information

- Ability to access information about the IOT device&#39;s cybersecurity state and other necessary data (e.g., trustworthy time) to provide the organization.

- Ability to preserve system state information. (24)
- Ability to provide IOT device settings to allow local and remote access to audit data, to and through the device interfaces. **(CEA:AS and LAI:EC. Possibly also LAI:IC)**
- Ability to provide IOT device settings to allow the user to assign audit controls access to specific roles or organization-define personnel. (LAI:RSM)
- Ability for the IOT device to identify unique users interacting with it to allow for user session monitoring.

## Event Identification and Monitoring

- The device can identify and monitor for organizationally defined cybersecurity events (e.g., expected state change) that may occur on or involving the IOT device.

- Ability to support a comprehensive list of events that are identified as necessary for a comprehensive auditing process by the organizational auditing policy.
- Ability to monitor for organizationally defined cybersecurity events
- Ability to support a monitoring process to check for disclosure of organizational information to unauthorized entities. (The device may be able to perform this check itself or provide the information necessary for an external process to check).
- Ability to monitor communications traffic. (7)
- Ability to detect remote activation attempts. (42)
- Ability to detect remote activation of collaborative computing device. (15)
- Ability to detect remote activation of sensors. (42)

## Event Response

- The device can respond to organizationally defined cybersecurity events in an organizationally defined way

  - Ability to generate alerts for events of interest (e.g., capacity thresholds). (5,18)
  - Ability to respond to alerts according to the predefined responses dictated by the auditing policies of the organization.
  - Ability to alert connected information systems of potential issues found during the auditing process or provide information to an external process that will issue these alerts.
  - Ability to notify users of activation of the collaborative computing device. (15)
  - Ability to provide a physical indicator of sensor use. (42)
  - In the event of an auditing failure, the IOT device needs to be able to respond appropriately according to the alert that was issued (either by the device or and external auditing process that interacts with the device)

Event Monitoring and Response (from Kevin earlier version)

- Ability for the IOT device to identify and log user logout. (23)

##

## Audit Support

- The device can generate audit logs for organizationally defined events
  - Ability to identify and capture the organizational/user defined events using a persistent method that can be reexamined later.
  - Ability to provide information related to specified cybersecurity events (e.g., cybersecurity state, timestamp) to the organization through organizationally defined means (e.g., logs).
  - Ability to create audit logs within the device for organization-defined and auditable events (e.g. account creation, modification, enabling, disabling, and removal actions and notifications). (7)
  - Ability to audit organization-defined and auditable events (e.g. account creation, modification, enabling, disabling, and removal actions and notifications) that are logged through device interfaces.
- The device can capture required information in audit logs
  - Ability to track users interacting with the device, the time they interacted with the device, and to list this information in an audit log
  - Ability to identify where organizationally defined events occurred, to support locating the source of the event, the time the event occurred, and the outcome of the event if there is one.
  - Ability to log information pertaining to: The type of event that occurred, The time that the event occurred, Where the event occurred, The source of the event, The outcome of the event, Identity of users/processes associated with the event.
  - Ability to support auditing of configuration actions (CM-5 (1), CM-5(2))
  - Ability to provide adequate information as to why it captured a particular event or set of events,
  - Ability to provide as much information as necessary for examination of security incidents.
- The device can maintain audit logs in accordance with organization policy.
  - Ability to store persistent audit logs up to a predefined size established by the user/organization.
  - Ability to establish the storage capacity for retaining audit logs that supports the predefined amount of time.
  - Ability to comply with organizational procedures for how long audit logs must be kept and the size they are allowed to grow to.
  - Ability to establish length of times to support organizationally defined policies for how long audit records are kept and how large audit records are allowed to be.
  - Ability to delete audit logs or send alerts that the logs are too big for the device to continue to store if the predefined amount of time has not yet passed to delete them.
- Ability to use timestamps to verify when an auditing event occurred.
  - Ability to support specified granularity in its timing measurements as predefined by the IOT device user.
  - Ability to use synchronization with a verified time source to determine the validity of a timestamp.
  - Ability to record timestamps that can be translated to Coordinated Universal Time (UTC) or Greenwich Mean Time (GMT) to support a standardized representation of timing.
- The device can provide information related to cybersecurity events through organizationally defined means.

- Ability to report on its cybersecurity state. [Source: NIST IR 8259]
- the ability to provide the appropriate audit information to the information system or organization to report on the state of the IOT device security.
- Ability to run an internal audit (automated or otherwise) to provide the information requested for an external process to audit the device.

- Ability to coordinate with other organizational entities that may be participating in the auditing process. It could possibly need to be able to reveal the results of its own event captures to an external auditing process by another device.
- Ability to provide the appropriate audit information to an (potentially automated) audit reduction process, where its auditing information can be checked to allow for review, analysis, and reporting
  - If the IOT device cannot support an audit reduction process itself, the IOT device must be able to provide this information to an external process in a way that provides all possible requested information.

- Ability to support an audit generation process for the information system by providing the information it needs (either by completing an audit generation of its own or by exposing its audit logs to an external process).Ability to support an alternate auditing process in the event that the primary auditing process fails.
- Ability to protect the audit information it provides to the information system according to organizational policy (e.g., the device may need to support encryption and data signing of its auditing files if necessary, as well as other access control protections).

## Event Identification Support (From Kevin in an earlier version)

- Ability to provide IOT device settings to allow for audit organization-defined and auditable events (e.g. account creation, modification, enabling, disabling, and removal actions and notifications) logged within the device. **(CEA:AEI, CEA:EIS, CEA:EMR)**
- Ability to provide IOT device settings to allow to for audit organization-defined and auditable events (e.g. account creation, modification, enabling, disabling, and removal actions and notifications) logged through device interfaces. **(CEA:AS)**

