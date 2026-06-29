

In this build I independently designed, assemble, and configure a mid-end desktop PC built for personal, productive, and system optimization. This project documents the full process from planning and assembly to BIOS configuration, OS installation, driver setup, and stress testing.

---

## System Specifications

| Component | Model |
|----------|------|
| **CPU** | AMD Ryzen 5 5600 (6-Core / 12-Thread) |
| **Motherboard** | MSI B550M PRO-VDH WIFI (AM4, mATX) |
| **Memory** | 32GB DDR4 (2x16GB Dual Channel) |
| **GPU** | NVIDIA GeForce RTX 4070 |
| **Storage (Primary)** | Samsung 990 PRO 1TB NVMe SSD |
| **Storage (Secondary)** | Seagate 2TB SATA HDD |
| **Power Supply** | ARESGAME AGV Series 500W, 80+ Bronze (Non-Modular) |
| **Cooling** | AMD Wraith Stock Cooler + Case Airflow System |

---

## Project Objectives

- Build a balanced gaming and productivity PC
- Ensure full hardware compatibility across all components
- Optimize BIOS, drivers, and OS configuration for performance
- Validate system stability through benchmarking and stress testing
- Document full build process for portfolio / GitHub showcase

---

## Planning & Compatibility Research

Before assembly, extensive research was performed to ensure system stability and compatibility:

### CPU & Motherboard
- Confirmed Ryzen 5 5600 support on MSI B550 chipset
- Verified BIOS compatibility for Ryzen 5000 series CPUs

### Memory Configuration
- Installed 32GB DDR4 in dual-channel (A2 + B2 slots)
- Ensured XMP support for rated memory performance

### GPU Integration (RTX 4070)
- Verified PCIe x16 Gen4 compatibility via B550 motherboard
- Confirmed physical clearance inside mATX chassis

### Storage Layout
- NVMe SSD dedicated to OS + applications
- HDD used for bulk storage and media files

### Power Supply Consideration
- Installed: **ARESGAME AGV 500W 80+ Bronze PSU**
- NVIDIA recommended PSU for RTX 4070: ~650W+

**Note:**
- System operates under normal load conditions
- Limited headroom for power spikes under heavy GPU stress
- Not ideal for overclocking or sustained high-power workloads
- Recommended future upgrade: 650W–750W high-quality PSU

---

## Assembly Process

### 1. CPU Installation
- Installed Ryzen 5 5600 into AM4 socket
- Aligned triangle markers for correct orientation
- Applied thermal paste (pea-sized method)
- Mounted stock AMD Wraith cooler

### 2. RAM Installation
- Installed 32GB DDR4 (2x16GB)
- Configured in dual-channel slots (A2 + B2)
- Verified proper seating and latch engagement

### 3. Storage Installation
- Installed Samsung 990 PRO NVMe SSD into M.2 slot
- Secured with heatsink
- Connected Seagate 2TB HDD via SATA data + power

### 4. Motherboard Installation
- Installed I/O shield
- Mounted motherboard on case standoffs
- Secured all mounting points evenly

### 5. Power Supply Installation
- Installed ARESGAME 500W PSU in bottom PSU chamber
- Routed cables:
  - 24-pin motherboard power
  - 8-pin CPU EPS power
  - PCIe GPU power
  - SATA power for HDD

**Note:** Non-modular PSU required full cable management planning for airflow efficiency.

### 6. GPU Installation
- Installed RTX 4070 into PCIe x16 slot
- Secured mounting bracket
- Connected PCIe power cable

### 7. Cable Management & Airflow
- Front intake airflow configuration
- Rear exhaust fan setup
- Routed cables behind motherboard tray
- Ensured unobstructed GPU airflow path

---

## BIOS / UEFI Configuration

After first boot, BIOS settings were optimized:

- Enabled **XMP profile** for RAM speed
- Verified NVMe SSD detection
- Set primary boot drive to NVMe
- Enabled **Resizable BAR** for GPU performance
- Monitored CPU temps and fan curves

---

## Operating System Installation

- Installed Windows 10 via USB boot media
- Installed on NVMe Samsung 990 PRO SSD
- Completed full Windows Update cycle
- Installed chipset, GPU, and motherboard drivers

### Installed Drivers:
- AMD B550 Chipset Drivers
- NVIDIA GeForce Drivers (RTX 4070)
- LAN / WiFi / Audio Drivers (MSI Support Package)

---

## Optimization & Configuration

- Enabled Hardware-Accelerated GPU Scheduling
- Configured NVIDIA Control Panel for performance mode
- Disabled unnecessary startup applications
- Verified full hardware recognition in Device Manager
- Updated BIOS (if required for stability improvements)

---

## Stress Testing & Benchmarks

### CPU Stability
- Cinebench R23 multi-core test
- Monitored thermals under sustained load

### GPU Stability
- 3DMark Time Spy benchmark
- Stress tested with GPU load simulation tools

### Storage Performance
- CrystalDiskMark benchmark
- Verified NVMe Gen4 performance on Samsung 990 PRO

### System Stability
- Combined CPU + GPU stress testing
- Monitored voltage, temperature, and power behavior

---

## Final Product

- Fast boot times (~10–15 seconds via NVMe SSD)
- Stable gaming performance at 1080p / 1440p
- Efficient multitasking with 32GB RAM
- Quiet idle operation with controlled thermals
- Stable driver and OS configuration after optimization

---

## Summary

This build demonstrates full-cycle PC development including:

- Hardware selection and compatibility planning
- Physical assembly and cable management
- BIOS/UEFI configuration
- Operating system installation and driver setup
- Performance validation and stress testing
