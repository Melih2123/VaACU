# VaACU
**Voltage and Amperage Control Unit**

VaACU is an open-source power management and battery charging platform designed to integrate multiple power sources into a single, organized system.

It supports **9–36 V DC input** and **220 V AC mains input**, converting incoming power into regulated **3.3 V, 5 V, and 12 V DC rails** while supporting battery charging, power-path management, current monitoring, and protection circuitry.

### Key Features
- Multiple power input options
- Regulated 3.3 V, 5 V, and 12 V power rails
- Integrated battery charging and backup power management
- Diode OR-ing for power-source isolation
- Current sensing using the INA293B2
- Fuse-based overcurrent protection
- Battery undervoltage protection
- ESP32-S3-based monitoring and control
- Open-source hardware design developed with KiCad

VaACU aims to provide a modular foundation for embedded systems that need flexible power input, battery backup, and centralized power management.

**Status:** Hardware design and validation hasnt been done, you the user might have to verify before usage.
