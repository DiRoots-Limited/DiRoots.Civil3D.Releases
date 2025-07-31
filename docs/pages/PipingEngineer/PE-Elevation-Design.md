---
layout: default
title: Elevation Design
parent: Piping Engineer User Guide
nav_order: 2
---

# Elevation Design
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Elevation Design

Piping Engineer provides system-aware piping elevation design capabilities that hold references during edits and offer options to auto-modify pipe elevation upstream/downstream.

## Overview

The Elevation Design feature enables precise control over piping network elevations while maintaining system integrity and connectivity. Key capabilities include:

- **Reference holding** during elevation modifications
- **Automatic upstream/downstream adjustments**
- **System-aware elevation calculations**
- **Slope validation** and optimization
- **Bulk elevation operations**

## System-aware Elevation Design

### Understanding System Awareness

Piping Engineer maintains awareness of the entire piping system when making elevation changes:

- **Network connectivity** is preserved during elevation modifications
- **Flow direction** is considered in elevation calculations
- **System type** influences elevation constraints and rules
- **Connection points** are maintained at appropriate elevations

![Piping Engineer system awareness](../../../assets\images\PipingEngineer\PE-SystemAwareness.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

### Reference Point Management

The tool allows you to establish and maintain reference points during elevation design:

1. **Select reference elements** (structures, fittings, or specific pipes)
2. **Set reference elevations** that will remain fixed during modifications
3. **Define elevation relationships** between connected elements
4. **Maintain reference integrity** throughout the design process

![Piping Engineer reference management](../../../assets\images\PipingEngineer\PE-ReferenceManagement.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

## Elevation Modification Options

### Manual Elevation Adjustment

Direct control over individual pipe and structure elevations:

Steps:
1. Select the pipe or structure you want to modify
2. Enter the new elevation value
3. Choose how to handle connected elements:
   - **Maintain connections** (adjust connected elements automatically)
   - **Break connections** (create gaps that need manual resolution)
   - **Hold references** (keep reference points fixed)

![Piping Engineer manual elevation](../../../assets\images\PipingEngineer\PE-ManualElevation.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

### Automatic Upstream/Downstream Modification

Intelligent elevation adjustments that propagate through the network:

#### Upstream Modification

When modifying a pipe elevation, automatically adjust upstream elements:

- **Maintain slope requirements** for upstream pipes
- **Adjust structure elevations** as needed
- **Preserve flow direction** and system integrity
- **Apply slope constraints** based on system type

![Piping Engineer upstream modification](../../../assets\images\PipingEngineer\PE-UpstreamModification.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

#### Downstream Modification

When modifying a pipe elevation, automatically adjust downstream elements:

- **Maintain slope requirements** for downstream pipes
- **Adjust structure elevations** as needed
- **Preserve flow direction** and system integrity
- **Apply slope constraints** based on system type

![Piping Engineer downstream modification](../../../assets\images\PipingEngineer\PE-DownstreamModification.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

## Slope Integration

### Slope-aware Elevation Design

Elevation modifications automatically consider slope requirements:

```yaml
# Slope Considerations:
- Minimum slope requirements for different pipe types
- Maximum slope constraints for system integrity
- Optimal slope ranges for efficient flow
- Slope transitions at connection points
```

![Piping Engineer slope integration](../../../assets\images\PipingEngineer\PE-SlopeIntegration.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

### Slope Validation

Real-time validation ensures elevation changes meet slope requirements:

- **Pre-modification checks** to identify potential slope violations
- **Real-time feedback** during elevation adjustments
- **Automatic slope optimization** suggestions
- **Error reporting** for slope constraint violations

![Piping Engineer slope validation](../../../assets\images\PipingEngineer\PE-SlopeValidation.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

## Bulk Elevation Operations

### Network-wide Elevation Adjustments

Perform elevation modifications across entire networks or network segments:

1. **Select the network** or network segment
2. **Choose the operation type**:
   - **Offset elevation** (add/subtract a value)
   - **Set absolute elevation** (set to specific values)
   - **Scale elevation** (multiply by a factor)
   - **Match reference** (align to reference elements)
3. **Apply the changes** with automatic upstream/downstream adjustment

![Piping Engineer bulk elevation](../../../assets\images\PipingEngineer\PE-BulkElevation.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

### Elevation Matching

Align multiple elements to reference elevations:

- **Match to structure** (align pipes to structure invert levels)
- **Match to grade** (align to site topography)
- **Match to floor** (align to building floor elevations)
- **Match to reference pipe** (align to existing pipe elevations)

![Piping Engineer elevation matching](../../../assets\images\PipingEngineer\PE-ElevationMatching.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

## Elevation Constraints

### System-specific Constraints

Different piping systems have different elevation constraints:

```yaml
# Sanitary Systems:
- Minimum slope: 2% (0.02 ft/ft)
- Maximum slope: 25% (0.25 ft/ft)
- Cover depth requirements
- Invert level constraints

# Storm Systems:
- Minimum slope: 1% (0.01 ft/ft)
- Maximum slope: 20% (0.20 ft/ft)
- Cover depth requirements
- Invert level constraints

# Water Systems:
- Pressure considerations
- Air vent requirements
- Minimum cover depth
- Maximum velocity constraints
```

![Piping Engineer elevation constraints](../../../assets\images\PipingEngineer\PE-ElevationConstraints.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

### Custom Constraint Management

Define and apply custom elevation constraints:

1. **Create constraint rules** for specific project requirements
2. **Apply constraints** to selected elements or networks
3. **Validate against constraints** before applying changes
4. **Override constraints** when necessary with proper documentation

![Piping Engineer custom constraints](../../../assets\images\PipingEngineer\PE-CustomConstraints.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

## Visualization and Preview

### 3D Elevation Preview

Visualize elevation changes before applying them:

- **3D preview** of proposed elevation modifications
- **Color-coded elevation** display
- **Slope visualization** with gradient indicators
- **Conflict highlighting** for potential issues

![Piping Engineer 3D preview](../../../assets\images\PipingEngineer\PE-3DPreview.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

### Elevation Reports

Generate detailed elevation reports:

- **Elevation summary** for selected elements
- **Slope analysis** and validation results
- **Change log** of elevation modifications
- **Constraint compliance** report

![Piping Engineer elevation reports](../../../assets\images\PipingEngineer\PE-ElevationReports.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub> 
