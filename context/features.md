# DOMI Sensor Features & Benefits

This document outlines DOMI Sensor's key products, features, benefits, and differentiators to inform content creation that drives design wins and customer acquisition.

## Core Value Propositions

### 1. **Vertical Integration — Chip to Module**
- **Feature**: Full-stack control from VCSEL/SPAD chip design through optical assembly, firmware, and algorithm development. 100% in-house R&D.
- **Benefit**: Tighter optimization between components means better performance (range, accuracy, power) than assembling third-party chips. Faster customization turnaround.
- **Conversion Angle**: "One partner, one team, one quality standard—from custom chip to mass production."

### 2. **Pin-to-Pin Drop-In Replacements**
- **Feature**: Industry-standard footprints and interfaces (LGA packages, MIPI/USB/Ethernet output), enabling direct replacement of existing sensor designs.
- **Benefit**: Upgrade performance without PCB redesign. Lower BOM cost, zero requalification of mechanical fit. Faster time-to-market for product improvements.
- **Conversion Angle**: "Drop in our sensor. Keep your design. Get 3.8× longer range at lower cost."

### 3. **100k Lux Ambient Light Immunity**
- **Feature**: Sensors maintain accurate ranging under direct sunlight (up to 100,000 lux) through multi-frequency modulation and advanced SPAD design.
- **Benefit**: Reliable performance from indoor darkness to outdoor noon—no sensor swap needed between environments.
- **Conversion Angle**: "One sensor for every lighting condition. No blinds, no compromises, no excuses."

### 4. **Customizable ToF Modules**
- **Feature**: Custom resolution (QVGA to VGA), interface (MIPI/USB/Ethernet), FOV, form factor, and optical design available for volume projects.
- **Benefit**: Get exactly the sensor your product needs—not an off-the-shelf compromise. Engineering team works directly with yours.
- **Conversion Angle**: "Your product is unique. Your depth sensor should be too. Custom modules from concept to mass production."

### 5. **dToF + iToF Technology Coverage**
- **Feature**: Both direct ToF (SPAD-based, single-photon detection) and indirect ToF (modulated continuous-wave) technologies across the product portfolio.
- **Benefit**: Choose the right technology for your use case—dToF for long range and outdoor robustness, iToF for high resolution and indoor precision.
- **Conversion Angle**: "dToF or iToF? We don't pick sides. We pick the right technology for your application."

### 6. **Multi-Platform SDK Support**
- **Feature**: Software development kits for ROS, Android, Windows, and Linux with unified APIs across all product lines.
- **Benefit**: Integrate once, scale across platforms. Reduced software engineering effort across product variants.
- **Conversion Angle**: "One SDK. Four platforms. Zero integration headaches."

### 7. **Global Supply & Support**
- **Feature**: Shenzhen-based R&D and manufacturing, serving 500+ partners across 15+ countries with sub-24-hour technical response.
- **Benefit**: Reliable supply chain with direct engineering access. No distributor gatekeepers between you and the engineers who designed the sensor.
- **Conversion Angle**: "Talk to the engineers who built your sensor. Response in 24 hours or less, anywhere in the world."

## Product Categories

### ToF Camera Modules (6 products)

3D depth cameras based on Time-of-Flight technology for robotics, AR/VR, people counting, and gesture recognition.

| Product | Resolution | Range | FOV | FPS | Interface | Dimensions | Key Spec |
|---------|-----------|-------|-----|-----|-----------|------------|----------|
| **DMAS2M001** | 40×30 (dToF) | 0.2–8m | 60°×45° | 10 | USB-C / FPC | 7g | SPAD LiDAR, 940nm, ~1W, 30klux outdoor |
| **DMOM2808D** | 320×240 | 0.2–5m | 71.8°×56.6° | 10–30 | MIPI CSI-2 | 21×9.5×6.33mm | 850nm 2W, 340mW, outdoor-capable |
| **DMOM2508CL** | 320×240 | 0.2–2m | 71.8°×56.6° | 10–30 | MIPI CSI-2 | 21×9.5×6.33mm | 940nm 3W, 340mW, AR/VR & gesture |
| **DMOM2501C** | 100×100 | Up to 6m | 44°×44° | 15/30 | MIPI CSI-2 | 21.6×9.1×5.4mm | 940nm 3W, 800mW, face recognition |
| **DM-PS2601-VGA** | 640×480 | 0.3–5m | 120°×90° | 30 | Ethernet | 65×65×60mm, 315g | Dual VCSEL, ARM Cortex-A7 + NPU, 5W |
| **DM-TOF-5005A** | 320×240 | 0.2–2m | 70°×50° | Up to 30 | USB 2.0 UVC | 90.7×17.2mm | Sigmastar SOC, <3W, dual orientation |

**Key Specs Highlights**:
- **DMAS2M001**: dToF SPAD array, 40×30 resolution, 0.2–8m range, 60°×45° FOV, 10 FPS, 940nm VCSEL, USB-C + FPC dual interface, 7g weight, ~1W power, anti-sunlight algorithm up to 30klux. Built for UAV altimetry, robot SLAM, volume measurement, and presence detection.
- **DMOM2808D**: Global shutter, 320×240, 15µm pixel, 1/3" sensor, 0.2–5m range, 71.8°×56.6° FOV, 850nm 2W VCSEL, MIPI CSI-2 2-lane, 340mW typical, ≤1% depth accuracy. Optimized for bright ambient light outdoor operation, mobile robotics, and automotive.
- **DMOM2508CL**: Global shutter, 320×240, 15µm pixel, 1/3" sensor, 0.2–2m range, 71.8°×56.6° FOV, 940nm 3W VCSEL, MIPI CSI-2 2-lane, 340mW typical, ≤1% or ≤1cm accuracy. Designed for AR/VR headsets, gesture tracking, 3D reconstruction, and people counting.
- **DM-PS2601-VGA**: VGA 640×480@30fps, 0.3–5m range, ultra-wide 120°×90° FOV, dual VCSEL projectors, Quad ARM Cortex-A7 + NPU + RISC-V MCU processor, 2GB DDR4 + 8GB eMMC, Ethernet output (TCP protocol), 5W avg / 15W peak. Purpose-built for people counting with onboard AI — outputs count, coordinates, height, and trajectory data without external hardware.

### RGBD Cameras (2 products)

Combined depth + RGB imaging in a single module for applications requiring both 3D data and color context.

| Product | ToF Resolution | RGB Resolution | Range | ToF FOV | RGB FOV | Interface | Dimensions | Power |
|---------|---------------|----------------|-------|---------|---------|-----------|------------|-------|
| **DM-RGBD-5002A** | 640×480@25fps | 1280×960@30fps | 0.2–5m | 64°×51° | 76°×61° | USB 2.0 | 79×35×15.7mm | <3.6W |
| **DM-RGBD-5003A** | 640×480@25fps | 1280×960@30fps | 0.2–5m | 64°×51° | 76°×61° | USB 2.0 | 79×35×15.7mm | <3.6W |

**Key Differentiators**:
- **DM-RGBD-5002A**: 940nm VCSEL, ±2% accuracy, USB bus-powered, Windows/Linux/Android/ROS support, Class I laser, –10°C to 45°C. On-board algorithm for low MPI and temperature drift.
- **DM-RGBD-5003A**: Same core specs as 5002A, USB bus-powered, multi-OS support including ROS. All-in-one integrated solution with VCSEL + driver IC + ToF sensor + RGB sensor + main processor.
- Both cameras deliver synchronized depth + color streams through a single USB 2.0 interface.

### ToF Sensors (4 products)

Compact 1D and 3D ranging sensors for proximity detection, presence sensing, and short-to-long range measurement.

| Product | Type | Range | Accuracy | FoV | FPS | Interface | Dimensions | Key Feature |
|---------|------|-------|----------|-----|-----|-----------|------------|-------------|
| **DM0301** | 1D dToF | 0.02–5m | <20mm | 25° | Up to 50Hz | I²C | 4.4×2.4×1.0mm | VL53L4CD pin-to-pin, 940nm, Class I, $1.45–$3.20 |
| **DMS604** | dToF Ranging | 0.05–58m indoor / 35m outdoor@100klux | ±1% >3m, <±30mm <3m | ≤1.3° | 50 | UART | 40×10×7.7mm | Proprietary SoC, 905nm, –20°C to 85°C |
| **DMOS5030A/5031A** | 3D ToF | 0.2–2.5m | ≤2% deviation | 60°×60° | Up to 20 | UART/SPI/I2C | 30×19×3.98mm | On-board Cortex M3 ISP, 940nm, <500mA |
| **DM-DTOF2002C0** | Proximity | 2–120cm | ±10%@120cm | 25° | ~28Hz | I²C/UART | 10×8×7.6mm | Sharp SPAD tech, 940nm, 10mA, Class I |

**Key Specs Highlights**:
- **DM0301**: Integrated VCSEL + SPAD + TDC + MCU in 4.40×2.40×1.00mm LGA package. Histogram and cross-talk algorithms embedded. Cover glass calibration, firmware upgrade via I²C, 0.9mA@1Hz idle. Pricing: $3.20@10pcs, $2.20@100, $1.90@1K, $1.45@5K.
- **DMS604**: Ultra-narrow 1.3° FoV for pinpoint ranging. Superior 100klux outdoor sunlight immunity. Advanced histogram + super-resolution algorithms. SiP design with narrow 10mm width. Targets AGV/AMR obstacle avoidance, drone altimetry, material level sensing, IoT parking/traffic.
- **DMOS5030A/5031A**: All-in-one module with on-board DM3602 ISP (Cortex M3). Embedded algorithms: range finding, multi-zone human sensing, gesture control, keystone correction, posture monitoring. Auto laser turn-off for eye safety. Designed for smart projectors, white goods, service robots, security lighting.

### VCSEL Laser Modules (4 products)

High-power Vertical Cavity Surface Emitting Laser modules for ToF illumination, LiDAR, industrial, and medical applications.

| Product | Peak Power | Wavelength | Package | Operation | Key Feature |
|---------|-----------|-----------|---------|-----------|-------------|
| **DMP300KP** | 300W | 905nm | 5.2×5.2×1.55mm AlN | Pulsed (5ns) | 40°×30° rectangular spot, 20% PCE |
| **DMP200W** | 200W | 980nm | Water-cooled | CW | Medical/industrial grade, 4–5 W/cm² |
| **DMP1KKM** | 70W/ch × 16ch | 905nm | 17.3×4.0×1.7mm AlN | Pulsed (1.5–2ns) | 16-channel linear array, individual drive |
| **DMP20S** | 18mW | 405nm | Standard | CW | Multi-junction, nanosecond response, 3° divergence |

**Key Specs Highlights**:
- **DMP300KP**: 300W peak @ 61A/25V, 5ns pulse, 0.025% duty cycle. AlN ceramic for thermal management. Optimized for ToF 3D scanning, AGV/drone obstacle avoidance, AR/VR SLAM, night vision IR illumination. Custom FOV and wavelength binning available.
- **DMP200W**: 200W CW @ 20A/45V typ. Integrated water-cooling for wavelength stability under high duty cycles. 980nm "Goldilocks" wavelength balancing absorption and penetration. Targets medical cosmetology, surgical lasers, laser plastic welding, additive manufacturing, and long-range flash LiDAR.
- **DMP1KKM**: 16-channel linear VCSEL array. 70W peak per channel @ 15A. 905nm, AlN ceramic. Enables multi-zone/steered illumination for edge detection, UAV multi-point proximity sensing, AGV navigation, and smart infrastructure.

**Key Differentiator**: All VCSELs support custom FOV, pulse characteristics, packaging, and wavelength binning for volume orders.

### Other Products

| Product | Type | Resolution | Range | FOV | Key Feature |
|---------|------|-----------|-------|-----|-------------|
| **DM-SV001-F1** | Binocular Face Recognition | 640×480 | 0.4–1.0m | 54°×68° | RISC-V + NPU, 0.3s recognition, ≥98% liveness TAR |
| **DMOM3006A** | ToF ISP Chip | — | — | — | MIPI RX+TX, DVP, DSP, ROI, HDR, calibration engine |

**Key Specs Highlights**:
- **DM-SV001-F1**: Binocular 3D face recognition module with real-time liveness detection rejecting photos, videos, masks. RISC-V dual-core + NPU with embedded AI engine. 64MB DDR3L + 16MB SPI NOR Flash. MIPI CSI interface, UART for communication. 4–9V input. Face comparison TAR ≥98% @ FAR=10⁻⁶. Designed for smart door locks, access control, POS, attendance, and financial identity verification.
- **DMOM3006A**: ToF ISP chip converting raw ToF sensor data into 14-bit distance + 12-bit IR + 8-bit ambient depth data. MIPI CSI-2 RX (2 lanes, 600Mbps) + TX (4 lanes, 3.2Gbps). DVP parallel interface. Real-time processing: ROI, 3×3 spatial filter, pixel calibration, distance non-linearity correction, temperature compensation, FOV compensation. Auto exposure and HDR smart sensing engine. Pair with DMOM5630A MIPI-USB converter board for USB 2.0 depth output.

## Technical Features by Category

### Depth Sensing Performance
- **dToF (Direct Time-of-Flight)**: Single-photon SPAD detection, 0.2–8m range, strong outdoor performance
- **iToF (Indirect Time-of-Flight)**: Modulated continuous-wave, VGA resolution, high indoor precision
- **Accuracy**: Millimeter to sub-centimeter depending on product and range
- **Frame Rate**: 10–50 FPS depending on model
- **Multi-Frequency Operation**: Reduces multi-path interference, improves stability across temperatures

### Optical Design
- **VCSEL Emitters**: In-house designed 905nm and 980nm emitters
- **SPAD Arrays**: Custom single-photon avalanche diode sensor arrays
- **Lens Options**: Multiple FOV configurations per product (narrow to wide)
- **Cover Glass Tolerance**: Designed for operation behind cover glass in consumer products

### Interface & Connectivity
- **MIPI CSI-2**: High-bandwidth video interface for camera modules
- **USB 2.0/3.0**: Plug-and-play connectivity for evaluation and integration
- **Ethernet**: Industrial-grade networking for factory and warehouse deployment
- **I2C**: Standard sensor control interface

### Software & SDK
- **ROS (Robot Operating System)**: Native ROS drivers for robotics integration
- **Android SDK**: Mobile and embedded Android support
- **Windows SDK**: Desktop development and evaluation
- **Linux SDK**: Embedded Linux and industrial computing
- **Unified API**: Consistent programming model across all DOMI products

### Calibration & Reliability
- **Per-Unit Factory Calibration**: Every module individually calibrated
- **Multi-Frequency/Exposure**: Adaptive to temperature and environmental changes
- **Eye Safety**: Class I eye-safe across all products
- **Industrial Temperature Range**: Rated for production environments

## Competitive Differentiators

### vs. STMicroelectronics (VL53L Series)
- **Pin-compatible replacements**: DM0301 drops into VL53L4CD designs with no PCB change
- **Longer range**: Up to 5m vs. 1.3m for equivalent ST parts
- **Better sunlight performance**: 100k lux vs. moderate ambient immunity
- **Lower cost**: Competitive unit pricing + reduced system BOM
- **Direct engineering access**: Talk to the design team, not a distributor FAE

### vs. Other ToF Module Vendors (Sony, AMS/OSRAM, Melexis)
- **Vertical integration advantage**: Chip design + module manufacturing under one roof
- **Customization speed**: In-house optical design means faster custom module turnaround
- **Broader portfolio**: dToF + iToF + VCSEL components from one vendor
- **Drop-in strategy**: Specifically designed to replace existing designs without requalification

### vs. Assemblers / Module Resellers
- **Not just assemblers**: We design the chips inside the module
- **Performance optimization**: Chip-module-algorithm co-design beats third-party assembly
- **Supply chain control**: No dependency on external chip vendors for core technology
- **True customization**: Custom chip variants possible for volume, not just mechanical repackaging

## Use Cases by Application

### Robotics & AMR
- Navigation and SLAM in dynamic environments
- Glass wall, cliff, and thin obstacle detection
- Multi-sensor fusion with 2D LiDAR and cameras
- Warehouse, hospital, and service robot deployment

### UAV & Drone
- Precision altimetry and terrain following
- Autonomous landing on varied surfaces
- Collision avoidance in all lighting conditions
- Optical flow augmentation for position hold

### Face Recognition & Security
- 3D liveness detection (anti-photo, anti-mask)
- Access control and smart door locks
- Payment authentication terminals
- Bank-grade biometric security

### Smart Home & IoT
- Privacy-compliant presence detection (no RGB image)
- Fall detection and elderly care monitoring
- Gesture-controlled appliances and lighting
- Room occupancy for HVAC optimization

### Volume Measurement & Logistics
- Parcel dimensioning for shipping cost calculation
- Pallet scanning and warehouse automation
- DWS (Dimensioning, Weighing, Scanning) systems
- Instant 3D measurement of irregular objects

### People Counting
- Retail foot traffic analytics with 98% accuracy
- Building occupancy monitoring
- Tailgating detection in secure areas
- GDPR-compliant (depth-only, no identifiable images)

### AR/VR & Spatial Computing
- Hand gesture tracking and recognition
- 6DoF controller-free interaction
- Room mapping and environment understanding
- Mixed reality object placement

### Industrial Automation
- Safety curtain replacement with 3D zone monitoring
- Robot arm calibration and workpiece positioning
- Defect detection on assembly lines
- Virtual fence and intrusion detection

## Company Proof Points

- **Founded**: 2016, Shenzhen, China
- **R&D Team**: 50+ engineers across optics, algorithms, and hardware
- **Leadership**: Ex-Analog Devices and STMicroelectronics engineers, 15+ years tier-1 semiconductor experience
- **Patents**: 30+ core technology patents
- **Global Reach**: 500+ partners across 15+ countries
- **Design**: 100% in-house design from chip to module
- **Response**: Sub-24-hour engineering support

## Contact & Inquiry Information

- **Email**: domi@domisensor.com
- **Phone**: (+86) 191 2943 4890
- **Address**: 905, Changhong Technology Building, Nanshan District, Shenzhen, China
- **Inquiry Fields**: Application (Robotics, Automotive, Drone, AR/VR, Volume Measurement, Face ID, People Counting, Other), Est. Annual Volume (<1K, 1K-10K, 10K-100K, >100K)
- **Social**: Facebook, YouTube, X (Twitter)

## Key Messaging for Conversions

### Design Win Conversion Messages
- "Drop-in replacement. Better specs. Lower cost. No PCB redesign."
- "Same footprint. Longer range. Sunlight-ready."
- "Custom ToF modules from prototype to mass production."
- "One sensor partner. Four product lines. Every application."
- "Talk to the engineers who designed your sensor—not a distributor."

### Pain Point Solutions
- **"Our sensor fails in direct sunlight"** → DOMI sensors maintain accuracy up to 100,000 lux ambient light.
- **"We're locked into a single vendor's ecosystem"** → Pin-compatible drop-in replacements with no redesign required.
- **"Custom modules take 6+ months from other vendors"** → In-house optical design and chip-level control enable faster customization.
- **"We can't get technical support from our supplier"** → Direct engineering access with sub-24-hour response.
- **"Our BOM cost is too high"** → Competitive unit pricing with lower integration and lifecycle cost.

### Social Proof Elements
- "500+ innovators empowered worldwide"
- "30+ core technology patents"
- "Deployed across 15+ countries"
- "50+ R&D specialists"
- "Founded by engineers with 15+ years at Analog Devices and STMicroelectronics"

## Content Creation Guidelines

When writing about DOMI Sensor products:

1. **Lead with specs, follow with context**: Engineers evaluate components by datasheets first, narrative second.
2. **Use comparison tables**: Head-to-head spec comparisons convert better than prose descriptions.
3. **Include real-world conditions**: Lab specs matter less than performance in sunlight, behind cover glass, across temperature.
4. **Be honest about trade-offs**: If DM0301 has a 20mm minimum range vs. VL53L4CD's 1mm, say so.
5. **Address integration explicitly**: What interface? What voltage? What SDK? What mechanical dimensions?
6. **Create clear next steps**: Datasheet download, sample request, evaluation kit, contact engineering.
7. **Match product to application**: Don't pitch a 1D ranging sensor to someone who needs a 3D depth camera.

---

*Note: Update this document as new products launch or specifications change. Keep messaging aligned with current product pages and datasheets.*
