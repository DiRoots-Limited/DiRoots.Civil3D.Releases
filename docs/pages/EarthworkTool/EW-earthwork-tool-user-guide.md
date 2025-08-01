---
layout: default
title: Earthwork Tool User Guide
nav_order: 4
has_children: true
permalink: /docs/earthwork-tool-user-guide
---

# Earthwork Tool User Guide

Learn how to use the Earthwork Tool to quickly and accurately compute earthwork cut and fill quantities, generate subgrade and base surfaces, and report volumes for construction workflows.
{: .fs-6 .fw-300 }

## Description

The Earthwork Tool helps you easily perform earthwork cut and fill volume calculations, including region-based volume calculations, topsoil stripping, and subgrade/base layer generation. It's your solution for construction earthwork workflows, built for accuracy and speed.

**Key Features:**
- **Full Volume Surface** - Complete surface comparison for cut/fill analysis
- **Region Volume Surfaces** - Multiple region-based calculations with defined boundaries
- **Topsoil Stripping** - Create stripping surfaces with configurable thickness
- **Subgrade/Base Surfaces** - Generate layered surfaces for construction
- **Dynamic Volume Units** - Switch between m³, yd³, ft³, acre-ft instantly
- **Object Association** - Select and isolate associated elements
- **Hierarchical Calculations** - Parent-child relationships with automatic totals

## Getting Started

### Main Interface

The Earthwork Tool is accessed through the DiRoots tab in Civil 3D. The main UI provides two primary calculation types:

- **Add Full Volume Surface** - Complete surface comparison across entire project
- **Add Region Volume Surfaces** - Region-specific calculations with defined boundaries

### Basic Workflow

1. **Open Earthwork Tool** from the DiRoots tab
2. **Choose Calculation Type** - Select full volume or region volume
3. **Select Surfaces** - Choose existing and proposed/future surfaces
4. **Configure Regions** (if applicable) - Define calculation boundaries
5. **Execute Calculations** - Run volume analysis
6. **Review Results** - Check cut/fill volumes and totals

## Calculation Types

### Full Volume Surface

Complete surface comparison for entire project area:

- **Surface Selection** - Choose existing and proposed/future surfaces
- **Civil 3D Compatibility** - Uses same calculations as Civil 3D dashboard
- **No Region Limitations** - Calculates across entire surface area
- **Total Volumes** - Provides complete cut/fill summary

**Use Case**: When you need to calculate total earthwork volumes for the entire project area.

### Region Volume Surfaces

Region-specific calculations with defined boundaries:

- **Defined Regions** - Use closed regions to limit calculation areas
- **Multiple Regions** - Add multiple regions for phased construction
- **Stripping Configuration** - Add or modify topsoil stripping per region
- **Hierarchical Results** - Parent-child relationships with automatic totals

**Use Case**: When you need to calculate volumes for specific areas or phases of construction.

## Advanced Features

### Hierarchical Calculations

The tool maintains parent-child relationships in calculations:

- **Child Elements** - Individual region calculations
- **Parent Totals** - Sum of all child elements within a region
- **Grand Totals** - Sum of full volume surface and all region volume surfaces
- **Automatic Updates** - Totals update automatically when components change

### Dynamic Unit Management

Switch between volume units instantly:

- **Unit Options** - m³, yd³, ft³, acre-ft
- **Dynamic Updates** - All calculations update immediately
- **Civil 3D Integration** - Units can also be configured in Civil 3D
- **Consistent Display** - All results shown in selected units

### Object Association

Manage and isolate associated elements:

- **Select Objects** - Choose elements associated with calculations
- **Isolate Elements** - Focus on specific components
- **Remove Items** - Delete unwanted elements from calculations
- **Real-time Updates** - Calculations update when elements are modified

## Workflow Examples

### Example 1: Full Surface Comparison

1. **Click "Add Full Volume Surface"** in the main UI
2. **Select Existing Surface** - Choose the current ground surface
3. **Select Proposed Surface** - Choose the future ground surface
4. **Execute Calculation** - Run the comparison
5. **Review Results** - Check total cut/fill volumes

### Example 2: Region-Based Calculations

1. **Click "Add Region Volume Surfaces"** in the main UI
2. **Select Defined Region** - Choose a closed region boundary
3. **Configure Surfaces** - Set existing and proposed surfaces
4. **Add Stripping** (optional) - Configure topsoil stripping thickness
5. **Execute Calculation** - Run the region analysis
6. **Add More Regions** - Repeat for additional areas

### Example 3: Validation and Verification

1. **Create Test Surface** - Generate a stripping surface with known thickness
2. **Compare Surfaces** - Use full volume surface to compare existing vs. stripping
3. **Verify Results** - Check that calculated volumes match expected values
4. **Adjust Parameters** - Modify settings as needed for accuracy

## Best Practices

### Surface Preparation
- **Verify Surface Integrity** - Ensure surfaces are complete and accurate
- **Check Region Boundaries** - Confirm regions are properly closed
- **Validate Input Data** - Verify surface elevations and boundaries
- **Test Calculations** - Run test calculations to verify accuracy

### Workflow Optimization
- **Start with Full Volume** - Begin with complete surface comparison
- **Add Regions Incrementally** - Add regions one at a time for better control
- **Use Descriptive Names** - Name regions and surfaces clearly
- **Document Settings** - Keep records of calculation parameters

### Quality Assurance
- **Cross-Reference Results** - Compare with Civil 3D calculations
- **Validate Totals** - Verify parent-child relationships are correct
- **Check Units** - Ensure consistent unit usage throughout
- **Review Associated Objects** - Verify correct element associations
