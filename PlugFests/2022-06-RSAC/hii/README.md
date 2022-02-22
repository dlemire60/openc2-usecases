# Huntington Ingalls at 2022-06 Plugfest

Huntington Ingalls (HII) will participate in the June 2022 Cybersecurity Automation Workshop (CAW) plugfest, as suppored by our DoD customer.

# Planned Contributions:

  - Implementation of [PACE](https://github.com/opencybersecurityalliance/PACE) use cases
    - Commanded retrieval of Software Bill of Material (SBOM) from a designated set of network components. Demonstrates:
      - OpenC2 [SBOM Actuator Profile (AP)](https://github.com/oasis-tcs/openc2-ap-sbom), currently under development
      - OpenC2 Posture Collection Service (PCS) AP, to be outlined by the HII engineering team as a by-product of the PACE prototyping activity
      - Posture Attribute Repository (PAR) API for storage and retrieval of collected posture attributes (expected to be developed by other plugfest contributors)
    - *Other PACE use cases TBD*
  - OpenC2 Integration Framework (OIF) [Orchestrator](https://github.com/oasis-open/openc2-oif-orchestrator) and [Device](https://github.com/oasis-open/openc2-oif-device) available for interoperability testing with other OpenC2 implementations.
    - Note that the OIF Orchestrator requires a JSON schema in order to create commands to send to OpenC2 Consumers
  - Operation of MQTT and OpenDXL brokers on Google Cloud Platform (GCP) to support messaging among plugfest components.
