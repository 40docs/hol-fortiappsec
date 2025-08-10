# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is the **hol-fortiappsec** repository - a hands-on lab module for FortiAppSec Cloud security training. It's part of the 40docs documentation platform ecosystem and contains interactive security training materials.

### Content Structure

This repository contains:

- **Landing Page**: `index.md` with custom CSS styling (`index.css`, `landing-page.css`)
- **Hands-on Labs**: Step-by-step security training modules in `hands-on-labs/`
  - `index.md` - Login and initial setup
  - `01-add-application.md` - Application configuration 
  - `02-enable-features.md` - Security feature enablement
  - `03-vulnerability-scan.md` - Vulnerability assessment
  - `04-attack.md` - Attack simulation and detection
- **Visual Assets**: Screenshots and images supporting the lab instructions
- **Branding Assets**: FortiNet branding elements (`fabric-white-full.gif`, `output.gif`)

### Content Format

- **MkDocs Integration**: All Markdown files use MkDocs front-matter YAML configuration
- **Image-Heavy Documentation**: Extensive use of screenshots to guide users through UI workflows
- **Step-by-Step Instructions**: Numbered procedures with corresponding visual aids
- **FortiAppSec Cloud Focus**: Specific to FortiNet's application security cloud platform

## Development Guidelines

### Content Editing
- Maintain step-by-step numbering consistency across lab modules
- Ensure all referenced images exist and are properly linked
- Use descriptive alt text for accessibility (currently minimal)
- Follow existing screenshot naming conventions (`service-action-step.png`)

### Image Management
- Screenshots should be clear and show relevant UI elements
- Maintain consistent resolution and quality across images
- Update screenshots when UI changes occur in FortiAppSec Cloud
- Store images in the same directory as referencing Markdown files

### Lab Sequence
The hands-on labs follow this learning progression:
1. **Setup/Login** - Access FortiAppSec Cloud portal
2. **Application Management** - Add and configure applications
3. **Security Configuration** - Enable protection features  
4. **Vulnerability Assessment** - Run security scans
5. **Attack Simulation** - Demonstrate security capabilities

### Content Validation
- Verify all FortiAppSec Cloud URLs and navigation paths remain current
- Test lab procedures against actual FortiAppSec Cloud interface
- Ensure all images load correctly in MkDocs deployment
- Validate that CSS styling renders properly across browsers

## Repository Context

This repository is deployed as part of the 40docs platform ecosystem:
- Content is automatically deployed via GitOps workflows
- No local build process required - changes deploy automatically
- Part of broader security training curriculum
- Integrates with parent 40docs orchestration system

## Security Training Focus

This lab module specifically covers:
- **Web Application Firewall (WAF)** configuration
- **Vulnerability scanning** procedures and interpretation
- **Attack simulation** and log analysis  
- **FortiAppSec Cloud** platform navigation and administration
- **Application security** best practices through hands-on exercises

The content is designed for security professionals learning FortiNet's application security solutions.