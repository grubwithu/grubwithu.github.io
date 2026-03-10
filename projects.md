---
layout: page
title: "Projects"
permalink: /projects/
---

# Projects

## Research Projects

### Hardware-Assisted Fuzzing for Embedded Systems (EuroSys 2026)
*2025-2026*

**Description**: Research on effective on-hardware fuzzing techniques for embedded operating systems. This work addresses the limitations of traditional software-based fuzzing when applied to hardware-dependent embedded systems, particularly those with real-time constraints.

**Technologies**: Hardware-in-the-loop testing, Custom FPGA setups, Embedded OS kernels (FreeRTOS, Zephyr, VxWorks), AFL-based fuzzing framework

**Key Contributions**:
- Developed hardware interaction modules for accurate vulnerability discovery
- Designed evaluation framework for real-time operating system components
- Implemented techniques to handle hardware dependencies in fuzzing workflows
- Contributed to the EuroSys 2026 paper "Effective On-Hardware Fuzzing of Embedded Operating Systems"

**Outcome**: Conference paper accepted at EuroSys 2026 (Third author)

### Robotic Kernel Security Framework
*Present*

**Description**: Developing a comprehensive security framework for robotic operating system kernels, focusing on vulnerability detection, runtime protection, and secure communication protocols.

**Technologies**: C/C++, Linux Kernel, ROS (Robot Operating System), QEMU, AFL (American Fuzzy Lop)

**Key Contributions**:
- Implemented kernel module for monitoring robotic system calls
- Developed fuzzing framework for robotic kernel interfaces
- Designed secure inter-process communication protocol for robotic systems

### Secure Real-Time Operating System for Robotics
*2025*

**Description**: Research on securing real-time operating systems used in critical robotic applications, focusing on timing attacks and resource management vulnerabilities.

**Technologies**: FreeRTOS, Zephyr, ARM Cortex-M, Security Protocols

### Cyber-Physical System Security Analysis
*2024*

**Description**: Analysis of security vulnerabilities in cyber-physical systems with focus on robotic applications in industrial environments.

**Technologies**: MATLAB/Simulink, Network Security Tools, Industrial Protocols

## Open Source Contributions

### Linux Kernel Security Patches
*Ongoing*

**Description**: Contributing security patches to the Linux kernel with focus on robotic and embedded system use cases.

### ROS Security Enhancements
*2025*

**Description**: Developed security enhancements for the Robot Operating System (ROS) ecosystem.

## Course Projects

### Secure Embedded System Design
*Graduate Course Project*

**Description**: Designed and implemented a secure embedded system with hardware security modules and secure boot process.

**Technologies**: ARM TrustZone, Secure Boot, Cryptographic Libraries

### Operating System Security Analysis
*Graduate Course Project*

**Description**: Comprehensive security analysis of a modern operating system kernel, focusing on privilege escalation vulnerabilities.

**Technologies**: Linux Security Modules, SELinux, AppArmor

---

<div class="project-notes">
  <p><i class="fas fa-lightbulb"></i> <strong>Note</strong>: Most projects are related to my research focus on robotic kernel security. Detailed code and documentation available upon request.</p>
</div>

<style>
.project-notes {
  padding: 15px;
  background-color: #fff3cd;
  border-left: 4px solid #ffc107;
  margin-top: 30px;
  border-radius: 4px;
  color: #856404;
}

.project-notes i {
  color: #856404;
  margin-right: 10px;
}
</style>