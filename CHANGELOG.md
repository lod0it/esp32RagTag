## Overview

RagTag is a compact environmental monitoring gadget designed specifically for motorbike riders, focusing on simplicity and reliability. It aims to provide essential data through straightforward technology integration without overwhelming users with unnecessary features or complexity.

This document outlines the core functionalities, development milestones, and technical specifications of the Rag feature set designed to enhance user experience through simplified interactions with ride-specific environmental data.

## Key Features

- **Real-Time Data Access**: Provides real-time updates on critical environmental parameters.
- **Simplified Interface**: User-friendly interface ensuring ease of use for riders focusing primarily on operational data pertinent to their riding conditions.

### Feature Highlights

- **Temperature Monitoring**: Displays current ambient temperature along with historical averages.
- **Weather Condition Summaries**: Provides simplified summaries of weather patterns (e.g., rain, fog) affecting ride conditions directly at the point of use.

## Technical Specifications

| Specification          | Details                                    |
|------------------------|--------------------------------------------|
| **Processor Type**     | [ESP32 S3 N16R8 -> Migrating in the future to ESP32 C3] |
| **Storage Capabilities** | Utilizes microSD card for data storage, allowing for long-term data retention. |
| **Sensors Used**       | Integrated sensors for temperature, humidity, and other critical environmental metrics. |
| **Communication Protocol** | Utilizes standard protocols such as I2C or SPI for sensor data transmission. |
| **Power Source**       | Designed to operate efficiently on low-power consumption setups, at the moment a 5V USB-C connection it's needed

## Development Milestones

- Initial Prototype Testing: Completed successfully with no major hardware issues.
- User Interface Optimization: Focus shifted towards enhancing the user interface for intuitive navigation and interaction.
- Environmental Data Integration: Full implementation of real-time data logging and updates on critical environmental parameters.

---

*Note: The above content is a simplified representation. Actual details would be fleshed out based on specific project requirements, including detailed specifications for sensors, software architecture diagrams, and comprehensive usage guidelines.*