# Smart Farming IoT Security

A cybersecurity architecture for a fictional smart-farming environment using sensors, automated irrigation and cloud monitoring.

## System
```text
Soil Sensors ─┐
Weather Sensor ├→ Gateway → Edge Processing → Cloud Dashboard
Water Sensor ──┘                 |
                                 ↓
                           Irrigation Control
```

## Security Concerns
Sensor spoofing, compromised actuators, weak credentials, insecure wireless communications, cloud compromise and availability attacks.

## Security Controls
Device identity, secure firmware, network segmentation, encrypted communications, strong cloud authentication, audit logging and manual fail-safe controls.

## Why Security Matters
An IoT compromise can affect both data and physical processes, making integrity and availability particularly important.
