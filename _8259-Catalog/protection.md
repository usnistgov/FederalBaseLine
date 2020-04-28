---
layout: default
title: Data Protection
navOrder: 3
navTitle: Protection
permalink: /protection/
---

# Data Protection

## Secure Execution

- Ability to establish setting to protect the execution of code on the IOT device.
- Ability to support IOT device shared system resources. (4)
  - Ability to release resources from the IOT device back to the associated system. (4)
  - Ability to separate user and process resources use. (4)
- Ability to enforce IOT device configuration execution policies. (18)
 
  _Requires some or all of the following depending on implementation:_

  - Ability for the IOT device to execute code in confined virtual environments. (18)
  - Ability to separate IOT device processes into separate execution domains. (39,44)
  - Ability to manage IOT device memory address space assigned to processes. (39)
  - Ability to enforce access by the IOT device to memory space through kernel. (39)
  - Ability to prevent an IOT device process from accessing memory space of another process. (39)
  - Ability to enforce configured IOT device disk quotas. (5)

- Ability to establish sufficient resources to store IOT device operating environment in ROM. (34)
- Ability to established sufficient code space in IOT device memory. (34)

## Secure Storage

- The IoT device can protect the data it stores from unauthorized access and modification. [Source: NIST IR 8259] (_alternate wording:_ Ability to secure data stored within the IOT device.)

	_Requires some or all of the following depending on implementation:_

  - Ability to secure IOT device data stored in remote storage areas (e.g., cloud, server, etc.).
  - Ability for the IoT device to utilize file compression technologies (5)
  - Ability for the IoT device to utilize separate partitions for system and user data (5)
  - Ability for the IoT device to utilize ROM for disk image/software (34)

- Ability for the IOT device to "sanitize" or "purge" specific or all data within the device.
- Ability to restrict physical access to removable storage on IOT devices.
- Ability to create audit logs showing the usage of the IOT device including access to stored data.
- Ability to support IOT device/media labeling/marking to support distribution, handling or types of information limitations (e.g., controlled information).

## Secure Transmission

- The IoT device can utilize one or more capabilities to protect the data it transmits from unauthorized access and modification. [Source: NIST IR 8259]

	_Requires some or all of the following depending on implementation_

  - Ability to enforce through the IOT device configuration settings traffic flow policies. (7)
  - Ability to utilize standardized protocols within the IOT device. (7)
  - Ability for the IOT device to establish network connections. (10)
  - Ability for the IOT device to terminate network connections (10)
  - Ability for the IOT device to de-allocate TCP/IP address/port pairings. (10)
  - Ability for the IOT device to establish communications paths. (11,23)
  - Ability for the IOT device to secure the communication paths. (11,23)
  - Ability for the IOT device to interface with DNS/DNSSEC. (20)
- Ability for the IOT device to use cryptographic means to validate integrity of data transmitted (23)
- Ability for the organization/user to establish through the IOT device interface the circumstances for when information sharing from the device and/or through the device interface will be allowed and prohibited.
  - The device needs to be able to expose this information in a secure way to authorized entities or processes.

## Cryptography Capabilities and Support

- Ability for the IOT device to use cryptography for data protection.

	_Requires some or all of the following depending on implementation:_

  - Ability for the IOT device to utilize sufficient resources to employ cryptographic mechanisms. (8,12,13,16,17,20,28,34)
  - Ability for the IOT device to obtain and validate certificates. (17)
  - Ability for the IOT device to verify digital signatures. (20,34)
  - Ability for the IOT device to run hashing algorithms. (28,34)
  - Ability for the IOT device to compute and compare hashes. (28,34)
  - ability for the IOT device to change keys securely. (8,12,13,16,17,20)
  - Ability for the IOT device to manage cryptographic keys securely.

    _Requires some or all of the following depending on implementation:_

    - Ability for the IOT device to generate key pairs (8, 12, 13, 17)
    - Ability for the IOT device to store encryption keys securely (8, 12, 13, 16, 17, 20, 28, 34)
    - Ability for the IoT device to change keys securely (8, 12, 13, 16 17, 20)

- Ability for the IOT device to support encryption of data at rest.
  - Ability for the IOT device to cryptographically store passwords at rest, as well as other authentication data.
  - Ability for the IOT device to support data encryption and signing to prevent data from being altered in device storage at rest.

- Ability for the IOT device to configure the cryptographic algorithm to protect data in transit.
  - Ability for the IOT device to support trusted data exchange with a specified minimum strength cryptography algorithm.
  - Ability for the IOT device to support data encryption and signing to prevent data from being altered in transit.

