# WARDEN

WARDEN is a removable Raspberry Pi 5-based rugged vehicle computer developed as an edge-compute, telemetry, logging, diagnostics, navigation, and AI-interface platform.

## Hardware Direction

- Raspberry Pi 5
- NVMe local storage
- CAN interface hardware
- rugged removable enclosure
- automotive power conversion and backup-power strategy
- serviceable connectors and modular panels

## Research Themes

- SocketCAN-based vehicle observation and logging
- local/offline model fallback
- system health monitoring
- modular enclosure and connector architecture
- safe startup and shutdown behavior
- deterministic separation between AI supervision and vehicle control

## Engineering Rule

Linux thinks. Deterministic hardware acts.

WARDEN may interpret, log, warn, summarize, and assist. Safety-critical vehicle functions remain outside the AI decision path.
