# Awesome Structured Text [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com) [![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

> A curated list of resources, tools, examples, and community content for IEC 61131-3 Structured Text (ST) programming.

Structured Text (ST) is a high-level, Pascal-like programming language used in industrial automation systems. It is one of the five programming languages defined in the IEC 61131-3 standard, commonly used in PLCs, HMIs, and embedded control systems.

Whether you're working with CODESYS, TwinCAT, Danfoss PLUS+1, or Siemens TIA Portal, this list helps you write better, more maintainable ST code.

## Latest Additions ✨
- [Top 20 Secure PLC Coding Practices](https://plc-security.com/) - Comprehensive guide for secure PLC programming
- [TwinCAT Performance Guide](https://infosys.beckhoff.com/english.php?content=../content/1033/tc3_plc_intro/3472167819.html) - Official performance optimization documentation
- [PLCOpen Safety Guidelines](https://www.plcopen.org/system/files/downloads/plcopen_safety_v1.0.pdf) - Safety programming guidelines

## Contents

- [Getting Started](#getting-started)
- [Code Patterns and Examples](#code-patterns-and-examples)
- [Libraries and Reusable Blocks](#libraries-and-reusable-blocks)
- [Tools & Simulators](#tools--simulators)
- [Vendor-Specific Resources](#vendor-specific-resources)
- [Security](#security)
- [Performance](#performance)
- [Testing & Debugging](#testing--debugging)
- [Learning and Tutorials](#learning-and-tutorials)
- [Communities](#communities)
- [Reference & Standards](#reference--standards)

## Getting Started

### Essential Resources 🌟
- [Introduction to IEC 61131-3](https://www.plcopen.org/iec-61131-3) - Official PLCopen introduction to the standard
- [CODESYS Free IDE](https://www.codesys.com/) - Industry standard development environment (v3.5 SP19)
- [OpenPLC](https://www.openplcproject.com/) - Open source PLC platform with ST support
- [Basic ST Syntax Reference (PDF)](https://www.fer.unizg.hr/_download/repository/Structured_Text_Tutorial.pdf) - Comprehensive syntax guide

### Development Setup & Tools
- [TwinCAT Development Guide](https://infosys.beckhoff.com/english.php?content=../content/1033/tc3_installation/index.html) - Official setup guide
- [CODESYS Development System](https://help.codesys.com/webapp/_cds_struct_installation;product=codesys;version=3.5.16.0) - Installation and setup
- [Siemens TIA Portal Setup](https://support.industry.siemens.com/cs/document/109761127/simatic-step-7-and-wincc-engineering-tools) - Configuration guide
- [Version Control Tools](https://alltwincat.com/2022/05/02/plc-programming-using-twincat-3-tutorial-part-13/) - Git setup for PLC projects
- [PLCnext Engineer](https://www.phoenixcontact.com/en-us/products/programming-software-plcnext-engineer-1046008) - Modern development environment

## Best Practices & Standards
- [PLCOpen Coding Guidelines](https://plcopen.org/guidelines) - Official coding standards
- [CODESYS Style Guide](https://help.codesys.com/webapp/_cds_tutorial_programming_guide;product=codesys;version=3.5.16.0) - Best practices and conventions
- [Siemens Programming Styleguide](https://support.industry.siemens.com/cs/document/81318674/programming-style-guide-for-s7-1200-and-s7-1500) - Official style recommendations
- [TwinCAT Best Practices](https://infosys.beckhoff.com/english.php?content=../content/1033/tc3_plc_intro/3472167819.html) - Coding guidelines
- [ISA 88/95 Templates](https://www.isa.org/standards-and-publications/isa-standards) - Industry standard templates

## Security

### Guidelines & Standards
- [Top 20 Secure PLC Coding Practices](https://plc-security.com/) - Comprehensive guide for implementing security in PLC code
- [ISA/IEC 62443](https://www.isa.org/standards-and-publications/isa-standards/isa-iec-62443-series-of-standards) - Industrial automation and control systems security
- [NIST SP 800-82](https://csrc.nist.gov/publications/detail/sp/800-82/rev-2/final) - Guide to Industrial Control Systems Security
- [PLCOpen Safety Guidelines](https://www.plcopen.org/system/files/downloads/plcopen_safety_v1.0.pdf) - Safety programming guidelines

### Implementation Examples
- [Secure PLC Project Examples](https://github.com/Fortiphyd/Secure_PLC_Coding) - Code examples for various PLC vendors
- [ISA99 Security Templates](https://www.isa.org/standards-and-publications/isa-standards/isa-standards-committees/isa99) - Security templates and examples
- [CISA ICS Security Resources](https://www.cisa.gov/topics/industrial-control-systems) - Government guidelines and tools

### Tools & Frameworks
- [ICS Security Assessment Tools](https://github.com/ITI/ICS-Security-Tools) - Collection of tools for ICS security testing
- [PLCScan](https://github.com/meeas/plcscan) - Tool for scanning PLC security configurations
- [Wireshark ICS Protocols](https://wiki.wireshark.org/ICS_Protocols) - Protocol analyzers for industrial networks

## Performance

### Optimization Guides
- [TwinCAT Performance Guide](https://infosys.beckhoff.com/english.php?content=../content/1033/tc3_plc_intro/3472167819.html) - Official optimization documentation
- [CODESYS Performance Tips](https://help.codesys.com/webapp/_cds_struct_reference_performance;product=codesys;version=3.5.16.0) - Best practices for performance
- [Siemens Optimizing Execution](https://support.industry.siemens.com/cs/document/59193558/simatic-s7-structured-programming) - Guide for S7 optimization

### Monitoring & Analysis
- [TwinCAT Analytics](https://www.beckhoff.com/en-us/products/automation/twincat/tfxxxx-twincat-3-functions/tf3500.html) - Performance analysis tools
- [CODESYS Professional Developer Tools](https://store.codesys.com/en/codesys-professional-developer-edition.html) - Profiling and optimization
- [Siemens SIMATIC ProDiag](https://new.siemens.com/global/en/products/automation/industry-software/automation-software/tia-portal/software/step7-professional/prodiag.html) - Performance diagnostics

### Real-world Examples
- [TwinCAT Optimization Case Studies](https://www.beckhoff.com/en-us/support/download-finder/application-examples/) - Performance improvement examples
- [PLCOpen Motion Examples](https://www.plcopen.org/system/files/downloads/tc2_motion_v11.pdf) - Optimized motion control
- [CODESYS Performance Patterns](https://help.codesys.com/webapp/_cds_example_performance_patterns;product=codesys;version=3.5.16.0) - Code patterns for better performance

## Testing & Debugging

### Testing Frameworks & Tools
- [PLC Logic Prover](https://www.controlx.io/plc-testing) - Automated testing framework for PLC programs
- [TwinCAT Test Suite](https://www.beckhoff.com/en-us/products/automation/twincat/tfxxxx-twincat-3-functions/tf3681.html) - Automated testing for TwinCAT projects
- [CODESYS Test Manager](https://store.codesys.com/en/codesys-test-manager.html) - Unit testing and continuous integration
- [PLCVerif](https://plcverif.cern.ch/) - Formal verification tool for PLC programs

### Debugging Tools
- [TwinCAT Analytics](https://www.beckhoff.com/en-us/products/automation/twincat/tfxxxx-twincat-3-functions/tf3500.html) - Advanced debugging and analytics
- [SIMATIC S7-PLCSIM Advanced](https://new.siemens.com/global/en/products/automation/industry-software/automation-software/tia-portal/software/plcsim-advanced.html) - Virtual commissioning and debugging
- [CODESYS Professional Developer Edition](https://store.codesys.com/en/codesys-professional-developer-edition.html) - Advanced debugging features

### Testing Guidelines & Resources
- [PLCOpen Conformity Testing](https://www.plcopen.org/system/files/downloads/tc3_conformity_v10.pdf) - Testing guidelines and certification
- [ISA 62381](https://www.isa.org/standards-and-publications/isa-standards/isa-standards-committees/isa62381) - Factory acceptance testing guidelines
- [IEC 61131-3 Testing Guide](https://www.iec.ch/dyn/www/f?p=103:38:0::::FSP_ORG_ID,FSP_APEX_PAGE,FSP_PROJECT_ID:1250,23,96973) - Official testing documentation

### Simulation Tools
- [Factory I/O](https://factoryio.com/) - 3D factory simulation for PLC testing
- [SIMIT](https://new.siemens.com/global/en/products/automation/industry-software/simit.html) - Virtual commissioning and simulation
- [Visual Components](https://www.visualcomponents.com/) - 3D manufacturing simulation

### Monitoring & Diagnostics
- [ProDiag](https://new.siemens.com/global/en/products/automation/industry-software/automation-software/tia-portal/software/step7-professional/prodiag.html) - Program diagnostics for SIMATIC
- [TwinCAT Scope](https://www.beckhoff.com/en-us/products/automation/twincat/tfxxxx-twincat-3-functions/tf3300.html) - Signal analysis and diagnostics
- [CODESYS Professional Developer Tools](https://store.codesys.com/en/codesys-professional-developer-edition.html) - Advanced monitoring features

### Best Practices & Examples
- [Testing Patterns for Industrial Automation](https://www.controleng.com/articles/system-integration-testing-best-practices/) - Common testing patterns
- [PLC Test Case Examples](https://github.com/PLCnext/PLCnext_CLI_Templates) - Example test cases and templates
- [Automated Testing Workflows](https://www.plctalk.net/qanda/showthread.php?t=101128) - Community discussion on testing practices

## Code Patterns and Examples

### Basic Patterns
- **Edge Detection**
  ```st
  // Rising edge detection example
  R_TRIG_inst(CLK := input_signal);
  IF R_TRIG_inst.Q THEN
      // Execute on rising edge
  END_IF
  ```
- **Timer Implementation**
  ```st
  // On-delay timer example
  TON_inst(IN := start_signal, PT := T#5S);
  IF TON_inst.Q THEN
      // Timer elapsed
  END_IF
  ```

### Advanced Patterns
- **State Machine Template**
  ```st
  TYPE E_States :
  (
      IDLE := 0,
      RUNNING := 1,
      ERROR := 99
  );
  END_TYPE
  ```
- **Data Handling**
  - Array manipulation
  - String processing
  - Structured data types

## Libraries and Reusable Blocks

> Function blocks and utilities you can drop into your project

- [Oscillator logic](#) *(add your own!)*
- [CAN decoding patterns](#)
- [Debounce logic block](#)
- *(You can grow this with user contributions)*

## Tools & Simulators

### Development Environments
- [CODESYS](https://www.codesys.com/) - Free for non-commercial use (v3.5 SP19)
  - Integrated visualization
  - Built-in simulator
  - Extensive library support
- [TwinCAT 3](https://www.beckhoff.com/en-us/products/automation/twincat/) - Free 7-day trial
  - Visual Studio integration
  - Real-time simulation
  - Motion control features

### Mobile Tools
- [PLC Ladder Simulator 2](https://play.google.com/store/apps/details?id=com.casdata.plc_ladder_simulator_2) - Android simulator with ST support
- [PLC Trainer](https://apps.apple.com/app/plc-trainer/id1523540923) - iOS learning platform
- [AutomationApps](https://play.google.com/store/apps/details?id=com.automationapps) - Reference and training

### Online Simulators
- [PLC Fiddle](https://www.plcfiddle.com/) - Browser-based PLC programming
- [ST Online](https://st-lang.com) - Interactive ST learning platform
- [PLCopen Simulator](https://www.plcopen.org/simulator) - Standard-compliant testing

### Development Tools
- Static Analysis
  - [TwinCAT Static Analysis](https://www.beckhoff.com/en-us/products/automation/twincat/tfxxxx-twincat-3-functions/tf1950.html) - Code quality checker
  - [CODESYS Static Analysis](https://store.codesys.com/en/codesys-static-analysis.html) - Code analysis tool
  - [PLCVerif](https://plcverif.cern.ch/) - Formal verification tool
- Code Generation
  - [TwinCAT Code Generator](https://www.beckhoff.com/en-us/products/automation/twincat/tfxxxx-twincat-3-functions/tf1910.html) - Code generation tool
  - [CODESYS Code Generator](https://store.codesys.com/en/codesys-application-composer.html) - Application composer
  - [Siemens SCL Generator](https://support.industry.siemens.com/cs/document/109479728/) - Code generation examples
- Project Templates
  - [TwinCAT Project Templates](https://github.com/Beckhoff/TF2000_TC3_Templates) - Official templates
  - [PLCnext Templates](https://github.com/PLCnext/PLCnext_CLI_Templates) - Project templates
  - [CODESYS Templates](https://store.codesys.com/en/application-templates.html) - Application templates

### Cross-Platform Tools
- Version Control
  - [Git Extensions](https://gitextensions.github.io/) - Git GUI client
  - [TortoiseGit](https://tortoisegit.org/) - Windows shell interface
  - [GitLab](https://about.gitlab.com/) - Git repository management
- Code Quality
  - [SonarQube](https://www.sonarqube.org/) - Code quality platform
  - [Jenkins](https://www.jenkins.io/) - Automation server
  - [Azure DevOps](https://azure.microsoft.com/en-us/products/devops) - Development platform
- Documentation
  - [Sphinx](https://www.sphinx-doc.org/) - Documentation generator
  - [MkDocs](https://www.mkdocs.org/) - Project documentation
  - [Read the Docs](https://readthedocs.org/) - Documentation hosting

## Vendor-Specific Resources

### CODESYS (v3.5+)
- [Official Documentation](https://content.helpme-codesys.com/en/CODESYS%20Development%20System/_cds_development_system_overview.html) - Complete development system documentation
- [Free ST samples](https://store.codesys.com/en/codesys-control-for-raspberry-pi-sl.html) - Example projects and templates
- [CODESYS Training](https://training.codesys.com/) - Official training materials and certifications
- [GitHub Examples](https://github.com/CODESYS-DevicePackage) - Device integration examples

### TwinCAT (Beckhoff)
- [TwinCAT 3 ST Guide](https://infosys.beckhoff.com/english.php?content=../content/1033/tcsample_plc_intro/537340955.html) - Comprehensive ST programming guide
- [TwinCAT 3 IDE](https://www.beckhoff.com/en-us/products/automation/twincat/) - Development environment (v3.1.4024.x)
- Performance Guidelines
  ```st
  // Optimized array handling
  FOR i := LOWER_BOUND(arr, 1) TO UPPER_BOUND(arr, 1) BY 1 DO
      // Process array elements
  END_FOR
  ```
- [Sample Projects](https://github.com/Beckhoff) - Official examples repository

### Siemens (TIA Portal)
- [ST Programming Guide](https://support.industry.siemens.com) - Official documentation (v17)
- [SCL Examples](https://support.industry.siemens.com/cs/document/109479728/) - Code examples
- Migration Guidelines
  - S7-300/400 to S7-1500
  - Step 7 to TIA Portal

### Danfoss PLUS+1 GUIDE
- [PLUS+1 GUIDE Overview](https://www.danfoss.com/en/products/dps/software/software-development/plus1-software/) - Latest version features
- [Application Examples](https://www.danfoss.com/en/products/dps/software/plus1-software/plus1-guide/plus1-guide-examples/) - Real-world implementations
- Best Practices
  - Memory optimization
  - Module organization
  - Communication protocols

## Learning and Tutorials

- [YouTube – The Automation Guy](https://www.youtube.com/c/TheAutomationGuy)
- [ST Programming with Codesys](https://www.youtube.com/playlist?list=PLuUJaDo5z4jRDOcrKqKpwhPvNT9HHlAO0)
- [PLC Academy](https://www.plcacademy.com/)
- [Engineer Mindset ST Blog Posts](https://www.electricalengineering.xyz/plc/structured-text-plc-programming/)

## Communities

### Official Forums
- [r/PLC on Reddit](https://www.reddit.com/r/PLC/) - Active community with 100k+ members
- [PLC Talk Forum](https://www.plctalk.net/qanda/) - Q&A platform for automation professionals
- [LinkedIn – IEC 61131-3 Groups](https://www.linkedin.com/search/results/groups/?keywords=iec%2061131-3) - Professional networking
- [Stack Overflow – Structured Text tag](https://stackoverflow.com/questions/tagged/structured-text) - Programming Q&A

### Events & Conferences
- Automation World Conference (Annual)
- PLCopen Technical Days
- Regional User Groups

## Reference & Standards

- [IEC 61131-3 Standard Summary](https://www.plcopen.org/iec-61131-3)
- [PLCopen](https://www.plcopen.org/)
- [GitHub Repos Using ST](https://github.com/search?q=structured+text+PLC)

## Contributors

Thanks goes to these wonderful people:

<!-- ALL-CONTRIBUTORS-LIST:START -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification.

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

Please ensure your pull request adheres to the following guidelines:

- Search previous suggestions before making a new one
- Make an individual pull request for each suggestion
- Use the following format: `[Resource Name](link) - Description.`
- Keep descriptions short and simple, but descriptive
- Start the description with a capital
- Check your spelling and grammar
- Make sure your text editor is set to remove trailing whitespace
- New categories or improvements to the existing categorization are welcome

Thank you for your suggestions!