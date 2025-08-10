# FortiAppSec Hands-On Lab

This repository contains hands-on security training materials for **FortiAppSec Cloud**, part of the 40docs documentation platform ecosystem.

## Overview

The FortiAppSec hands-on lab provides step-by-step training on Fortinet's application security cloud platform, covering web application firewall configuration, vulnerability assessment, and attack simulation.

## Lab Structure

### Getting Started
- **Landing Page**: `index.md` - Main entry point with navigation
- **Login Setup**: `hands-on-labs/index.md` - Access FortiAppSec Cloud portal

### Training Modules

1. **[Add Application](hands-on-labs/01-add-application.md)** - Configure applications for protection
2. **[Enable Features](hands-on-labs/02-enable-features.md)** - Activate security controls
3. **[Vulnerability Scan](hands-on-labs/03-vulnerability-scan.md)** - Assess application security
4. **[Attack Simulation](hands-on-labs/04-attack.md)** - Demonstrate protection capabilities

## Prerequisites

- Access to FortiAppSec Cloud via [support.fortinet.com](https://support.fortinet.com)
- Basic understanding of web application security concepts
- Familiarity with web application firewalls (WAF)

## Learning Objectives

By completing this lab, participants will:

- Navigate the FortiAppSec Cloud interface
- Configure application protection policies
- Execute vulnerability scans and interpret results
- Simulate attacks and analyze security logs
- Understand FortiNet's application security approach

## Lab Features

- **Visual Guidance**: Comprehensive screenshots for each step
- **Progressive Learning**: Builds complexity through sequential modules
- **Hands-On Experience**: Direct interaction with FortiAppSec Cloud
- **Real-World Scenarios**: Practical security assessment workflows

## Technical Details

### Content Format
- **MkDocs Compatible**: Uses front-matter YAML for deployment
- **Image-Rich**: Extensive visual aids for UI navigation
- **Responsive Design**: Custom CSS for optimal viewing experience

### Deployment
This lab is automatically deployed as part of the 40docs platform:
- GitOps-based deployment via Flux v2
- No local build process required
- Integrates with broader security curriculum

## Usage

### For Learners
1. Start with the main `index.md` page
2. Follow the login instructions in `hands-on-labs/index.md`
3. Progress through modules 01-04 in sequence
4. Use screenshots to verify correct UI navigation

### For Instructors
- All lab materials are self-contained
- Screenshots provide clear checkpoint validation
- Progressive complexity enables flexible pacing
- Can be integrated with broader security training programs

## Contributing

This repository is part of the 40docs ecosystem. When updating content:

1. Ensure all referenced images are included and properly linked
2. Maintain consistent screenshot quality and resolution
3. Update navigation paths if FortiAppSec Cloud UI changes
4. Test all procedures against current platform version
5. Follow existing numbering and formatting conventions

## Support

For technical issues or questions about FortiAppSec Cloud, refer to:
- [Fortinet Support Portal](https://support.fortinet.com)
- FortiAppSec Cloud documentation
- 40docs platform administration

## Repository Context

This is an independent Git repository within the 40docs multi-repository ecosystem:
- **Repository URL**: https://github.com/40docs/hol-fortiappsec.git
- **Platform**: 40docs Documentation as Code platform
- **Deployment**: Automated via GitOps workflows
- **Integration**: Part of comprehensive security training curriculum