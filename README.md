# Outlaw Engineering Research

Independent applied engineering research and prototyping focused on rugged edge computing, automotive electronics, vehicle networks, embedded systems, and AI-assisted engineering.

## Research Focus

- Rugged edge-compute architecture for vehicle and shop environments
- Automotive CAN observation, integration, logging, and diagnostics
- Separation of AI supervision from deterministic safety-critical control
- Modular embedded hardware, power distribution, and serviceable enclosure design
- Multimodal engineering workflows combining software, electronics, fabrication, and field testing
- Rapid prototyping with 3D printing, bench simulation, and revision-controlled CAD

## Active Research Platforms

### WARDEN

WARDEN is a removable Raspberry Pi 5-based vehicle computer being developed as an edge-compute, logging, diagnostic, navigation, and AI-interface platform.

Current work includes:

- Linux + SocketCAN vehicle telemetry
- NVMe-backed logging and local storage
- Raspberry Pi CAN hardware integration
- local/offline model fallback
- rugged modular enclosure development
- power-up, shutdown, recovery, and serviceability
- deterministic boundaries for vehicle-control functions

WARDEN is intended to supervise, log, warn, and assist. Safety-critical steering, braking, throttle, and primary engine operation are not dependent on an AI model.

[WARDEN project notes](docs/WARDEN.md)

### FENRIR

FENRIR is an experimental vehicle integration platform based on a 2012 Jeep Wrangler JKU. It combines a GM performance powertrain with custom drivetrain, suspension, steering, vehicle electronics, CAN integration, cameras, logging, and edge-compute systems.

Research areas include:

- multi-network CAN observation and integration
- vehicle-state modeling and telemetry
- bench validation before live-vehicle connection
- power-distribution architecture
- camera and sensor integration
- modular serviceable electronics packaging
- harness and system-routing validation

[FENRIR project notes](docs/FENRIR.md)

### ODIN / TV-PI

ODIN is a Raspberry Pi 5-based shop development and test node used for software prototyping, local-model testing, dashboards, remote access, and workflow experimentation before concepts are deployed into WARDEN.

[ODIN project notes](docs/ODIN.md)

## Development Method

The work is iterative and hardware-first:

1. Bench-test individual subsystems
2. Verify deterministic behavior
3. Document known-good checkpoints
4. Prototype enclosures and mounts
5. Validate physical fit and service access
6. Connect to the live vehicle only after bench validation
7. Preserve working revisions in version control

## Public Research Record

This repository is a public-facing overview of independent engineering research and development. It intentionally excludes private credentials, customer information, sensitive configuration data, and unpublished low-level vehicle-network details.

GitHub: [@laznat2-cpu](https://github.com/laznat2-cpu)
