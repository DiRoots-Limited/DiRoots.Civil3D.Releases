---
layout: default
title: Slope Validation
parent: Piping Engineer User Guide
nav_order: 4
---

# Slope Validation
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Slope Validation

Piping Engineer provides comprehensive slope validation capabilities that allow you to validate applied rules to the network and override slope rules for quick slope checks.

## Overview

The Slope Validation feature ensures your piping networks meet design standards and regulatory requirements. Key capabilities include:

- **Rule-based validation** against industry standards
- **Custom rule creation** for project-specific requirements
- **Slope override capabilities** for design flexibility
- **Real-time validation** during design modifications
- **Comprehensive reporting** of validation results

## Rule-based Validation

### Understanding Slope Rules

Piping Engineer applies slope rules based on industry standards and best practices:

```yaml
# Standard Slope Rules:
- Sanitary Systems: 2% minimum slope
- Storm Systems: 1% minimum slope
- Water Systems: Pressure-based (no minimum slope)
- Gas Systems: Pressure-based (no minimum slope)
- Process Piping: System-specific requirements
```

![Piping Engineer slope rules](../../../assets\images\PipingEngineer\PE-SlopeRules.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

### Applying Validation Rules

Steps to validate your piping network against established rules:

1. **Select the network** or network segment to validate
2. **Choose validation scope**:
   - **Entire network**: Validate all pipes in the system
   - **Selected elements**: Validate only selected pipes
   - **Network segment**: Validate a specific portion of the network
3. **Run validation** to check against applicable rules
4. **Review results** and address any violations

![Piping Engineer applying rules](../../../assets\images\PipingEngineer\PE-ApplyingRules.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

## Custom Rule Creation

### Creating Project-specific Rules

Define custom slope rules for your specific project requirements:

Steps:
1. **Access the Rules Manager** in the main interface
2. **Create new rule** with custom parameters:
   - **Rule name** and description
   - **Applicable systems** (sanitary, storm, etc.)
   - **Pipe size ranges** for the rule
   - **Minimum and maximum slope** values
   - **Special conditions** or exceptions
3. **Save the rule** to your project or profile
4. **Apply the rule** to your validation process

![Piping Engineer custom rules](../../../assets\images\PipingEngineer\PE-CustomRules.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

### Rule Categories

Organize your validation rules into logical categories:

```yaml
# Rule Categories:
- Code Requirements: Based on local building codes
- Industry Standards: Based on professional standards
- Project Specifications: Based on project requirements
- Client Requirements: Based on client preferences
- Quality Control: Based on internal quality standards
```

![Piping Engineer rule categories](../../../assets\images\PipingEngineer\PE-RuleCategories.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

## Slope Override Capabilities

### Quick Slope Override

Override slope rules for specific design situations:

Steps:
1. **Select the pipe** or pipe segment requiring override
2. **Choose override type**:
   - **Temporary override**: For design exploration
   - **Permanent override**: For approved design changes
   - **Conditional override**: Based on specific conditions
3. **Specify override parameters**:
   - **New slope value** or range
   - **Override reason** and justification
   - **Override duration** (if temporary)
4. **Apply the override** with proper documentation

![Piping Engineer slope override](../../../assets\images\PipingEngineer\PE-SlopeOverride.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

### Override Management

Manage and track slope overrides throughout your project:

- **Override log** with history and reasons
- **Approval workflow** for permanent overrides
- **Expiration tracking** for temporary overrides
- **Override reporting** for project documentation

![Piping Engineer override management](../../../assets\images\PipingEngineer\PE-OverrideManagement.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>
