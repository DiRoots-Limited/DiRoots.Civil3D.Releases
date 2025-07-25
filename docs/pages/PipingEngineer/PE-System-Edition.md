---
layout: default
title: System Edition
parent: Piping Engineer User Guide
nav_order: 3
---

# System Edition
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# System Edition

Piping Engineer provides flexible system edition capabilities that allow you to work with piping networks by network, specific elements, or by picking the start and end of the network.

## Overview

The System Edition feature offers three main approaches to selecting and editing piping systems:

- **Network-based selection**: Work with entire piping networks
- **Element-based selection**: Focus on specific pipes or structures
- **Start/End point selection**: Define network boundaries by picking start and end points

## Network-based System Edition

### Selecting by Network

This method allows you to work with entire piping networks as cohesive units.

Steps:
1. Select the "Network" option in the System Edition tab
2. Choose from available piping networks in your model:
   - **Sanitary Systems**
   - **Storm Systems**
   - **Domestic Water Systems**
   - **Fire Protection Systems**
   - **Other MEP Systems**

![Piping Engineer network selection](../../../assets\images\PipingEngineer\PE-NetworkSelection.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

### Network Properties

When working with networks, you can access and modify:

- **System-wide properties** that affect all elements in the network
- **Network topology** and connectivity
- **Flow direction** and system type
- **Network-level parameters** and calculations

![Piping Engineer network properties](../../../assets\images\PipingEngineer\PE-NetworkProperties.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

## Element-based System Edition

### Selecting Specific Elements

This approach allows you to focus on particular pipes or structures within your piping systems.

Steps:
1. Select the "Elements" option in the System Edition tab
2. Choose your selection method:
   - **Pre-select in Civil 3D**: Select elements in the Civil 3D model first
   - **Pick from List**: Choose from a list of available elements
   - **Filter by Properties**: Use property filters to select elements

![Piping Engineer element selection](../../../assets\images\PipingEngineer\PE-ElementSelection.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

### Element Filtering

Use advanced filtering options to select specific elements:

```yaml
# Filter Options:
- System Type: Filter by piping system category
- Material: Filter by pipe/structure material
- Size Range: Filter by diameter or dimensions
- Elevation Range: Filter by elevation values
- Connection Type: Filter by fitting or connection type
- Custom Parameters: Filter by any custom project parameters
```

![Piping Engineer element filtering](../../../assets\images\PipingEngineer\PE-ElementFiltering.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

## Start/End Point Selection

### Picking Network Boundaries

This method allows you to define network segments by selecting start and end points.

Steps:
1. Select the "Start/End Points" option in the System Edition tab
2. Click "Pick Start Point" and select the starting element in your model
3. Click "Pick End Point" and select the ending element in your model
4. The tool will automatically select all elements between the start and end points

![Piping Engineer start end selection](../../../assets\images\PipingEngineer\PE-StartEndSelection.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

### Network Path Analysis

When using start/end point selection, the tool provides:

- **Path visualization** showing the selected network segment
- **Element count** and type breakdown
- **Connection validation** to ensure path continuity
- **Alternative path suggestions** if multiple routes exist

![Piping Engineer path analysis](../../../assets\images\PipingEngineer\PE-PathAnalysis.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

## System-aware Editing

### Maintaining Network Integrity

All system edition methods maintain the integrity of your piping networks:

- **Connection preservation** during edits
- **Flow direction** maintenance
- **System type** consistency
- **Topology validation** after changes

![Piping Engineer system integrity](../../../assets\images\PipingEngineer\PE-SystemIntegrity.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

### Bulk Operations

Perform bulk operations across selected systems:

1. **Select multiple systems** or elements
2. **Apply changes** to all selected items simultaneously
3. **Validate results** to ensure network integrity
4. **Preview changes** before applying

![Piping Engineer bulk operations](../../../assets\images\PipingEngineer\PE-BulkOperations.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

## Validation and Error Checking

### Pre-edit Validation

Before applying changes, the tool validates:

- **Network connectivity** and completeness
- **Parameter compatibility** across selected elements
- **System type** consistency
- **Elevation** and slope constraints

![Piping Engineer pre-edit validation](../../../assets\images\PipingEngineer\PE-PreEditValidation.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

### Post-edit Validation

After applying changes, the tool checks:

- **Network integrity** maintenance
- **Parameter consistency** across the system
- **Connection validity** and flow direction
- **Error reporting** for any issues found

![Piping Engineer post-edit validation](../../../assets\images\PipingEngineer\PE-PostEditValidation.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

## Undo and Redo

### Change Management

Piping Engineer provides comprehensive change management:

- **Undo operations** to revert recent changes
- **Redo operations** to reapply undone changes
- **Change history** tracking for audit purposes
- **Selective undo** for specific operations

![Piping Engineer undo redo](../../../assets\images\PipingEngineer\PE-UndoRedo.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub> 
