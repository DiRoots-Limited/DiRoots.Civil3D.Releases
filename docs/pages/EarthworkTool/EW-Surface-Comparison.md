---
layout: default
title: Surface Comparison
parent: Earthwork Tool User Guide
nav_order: 1
---

# Surface Comparison
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Surface Comparison

The Earthwork Tool provides comprehensive surface comparison capabilities for calculating cut and fill volumes across entire project areas. The Full Volume Surface feature enables complete surface analysis with Civil 3D compatibility.

## Overview

Full Volume Surface comparison allows you to calculate cut and fill quantities by comparing two surfaces across the entire project area. This feature uses the same calculation methods as Civil 3D's dashboard feature, ensuring consistency and accuracy in your earthwork calculations.

## Full Volume Surface Workflow

### Accessing the Feature

1. **Open Earthwork Tool** from the DiRoots tab
2. **Main UI** - The tool displays the main interface with calculation options
3. **Add Full Volume Surface** - Click this option to create a new full volume calculation

### Surface Selection Process

1. **Select Existing Surface**
   - Choose the current ground surface from available surfaces
   - This represents the existing conditions before construction

2. **Select Proposed/Future Surface**
   - Choose the proposed or future ground surface
   - This represents the final design conditions

3. **Execute Calculation**
   - Click the execute button to run the comparison
   - The tool performs the same calculations as Civil 3D dashboard

### Calculation Results

The tool provides comprehensive volume analysis:

- **Cut Volume** - Total volume of material to be removed
- **Fill Volume** - Total volume of material to be added
- **Net Volume** - Difference between cut and fill
- **Unit Display** - Results shown in selected units (m³, yd³, ft³, acre-ft)

![Earthwork Tool surface comparison](../../../assets/images/EarthworkTool/EW-SurfaceComparison.gif)
<sub>Note: the version on the image may not reflect the latest version of Earthwork Tool.</sub>

## Civil 3D Compatibility

### Same Calculation Methods

The Earthwork Tool uses identical calculation methods to Civil 3D:

- **Dashboard Feature** - Same algorithms as Civil 3D's dashboard
- **Volume Accuracy** - Consistent results between tools
- **Surface Handling** - Compatible with all Civil 3D surface types
- **Data Integrity** - Maintains Civil 3D data standards

### Validation and Verification

Use the tool to validate Civil 3D calculations:

1. **Run Civil 3D Dashboard** - Perform calculation in Civil 3D
2. **Run Earthwork Tool** - Perform same calculation in Earthwork Tool
3. **Compare Results** - Verify volumes match between tools
4. **Cross-Reference** - Use for quality assurance and validation

## Advanced Features

### Dynamic Unit Management

Switch between volume units instantly:

- **Unit Options** - m³, yd³, ft³, acre-ft
- **Real-time Updates** - All results update immediately
- **Civil 3D Integration** - Units can also be configured in Civil 3D
- **Consistent Display** - All calculations shown in selected units

### Object Association

Manage associated elements:

- **Select Objects** - Choose elements related to the calculation
- **Isolate Elements** - Focus on specific components
- **Remove Items** - Delete unwanted elements
- **Real-time Updates** - Calculations update when elements change

## Workflow Examples

### Example 1: Basic Surface Comparison

1. **Click "Add Full Volume Surface"** in the main UI
2. **Select Existing Surface** - Choose current ground surface
3. **Select Proposed Surface** - Choose future ground surface
4. **Execute Calculation** - Run the comparison
5. **Review Results** - Check total cut/fill volumes

### Example 2: Validation with Civil 3D

1. **Create Civil 3D Dashboard** - Run calculation in Civil 3D
2. **Run Earthwork Tool** - Perform same calculation
3. **Compare Results** - Verify volumes match
4. **Document Differences** - Note any discrepancies for investigation

### Example 3: Unit Conversion

1. **Run Calculation** - Execute full volume surface comparison
2. **Change Units** - Switch from m³ to yd³
3. **Verify Conversion** - Check that results update correctly
4. **Export Results** - Save in preferred units

## Best Practices

### Surface Preparation
- **Verify Surface Integrity** - Ensure surfaces are complete and accurate
- **Check Surface Boundaries** - Confirm surfaces cover the same area
- **Validate Elevations** - Verify surface elevation data is correct
- **Test Calculations** - Run test calculations to verify accuracy

### Workflow Optimization
- **Start with Full Volume** - Begin with complete surface comparison
- **Use Descriptive Names** - Name surfaces clearly for easy identification
- **Document Settings** - Keep records of calculation parameters
- **Regular Validation** - Periodically compare with Civil 3D results

### Quality Assurance
- **Cross-Reference Results** - Compare with Civil 3D calculations
- **Check Unit Consistency** - Ensure consistent unit usage
- **Validate Surface Selection** - Verify correct surfaces are selected
- **Review Associated Objects** - Check element associations
