---
layout: default
title: Region Calculations
parent: Earthwork Tool User Guide
nav_order: 2
---

# Region Calculations
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Region Calculations

The Earthwork Tool provides comprehensive region-based volume calculations, allowing you to define specific areas and calculate cut and fill volumes for each region separately. This feature supports hierarchical calculations with parent-child relationships.

## Overview

Region Volume Surfaces enable you to perform targeted volume calculations within defined boundaries. Unlike full volume surface calculations, region calculations allow you to focus on specific areas of your project, making it ideal for phased construction, zones with different requirements, or areas requiring special attention.

## Region Volume Surfaces Workflow

### Accessing the Feature

1. **Open Earthwork Tool** from the DiRoots tab
2. **Main UI** - The tool displays the main interface with calculation options
3. **Add Region Volume Surfaces** - Click this option to create region-based calculations

### Region Definition Process

1. **Select Defined Region**
   - Choose a closed region boundary from your drawing
   - The region must be properly closed for accurate calculations
   - Multiple regions can be added to the same calculation

2. **Configure Surfaces**
   - Select existing surface for current conditions
   - Select proposed/future surface for design conditions
   - Configure additional parameters as needed

3. **Add Stripping Configuration** (Optional)
   - Configure topsoil stripping thickness for the region
   - Set stripping depth (e.g., 0.1m, 0.2m)
   - Stripping affects the calculation results

4. **Execute Calculation**
   - Run the region analysis
   - View individual region results
   - Check hierarchical totals

### Hierarchical Calculation Structure

The tool maintains parent-child relationships in calculations:

#### Child Elements
- **Individual Region Calculations** - Each region's cut/fill volumes
- **Stripping Adjustments** - Topsoil removal calculations per region
- **Surface Comparisons** - Region-specific surface analysis

#### Parent Totals
- **Region Group Totals** - Sum of all child elements within a region group
- **Stripping Totals** - Total stripping volumes across regions
- **Surface Totals** - Combined surface comparison results

#### Grand Totals
- **Full Project Totals** - Sum of full volume surface and all region volume surfaces
- **Complete Earthwork Summary** - Total project cut/fill requirements
- **Automatic Updates** - Totals update when components change

![Earthwork Tool region calculations](../../../assets/images/EarthworkTool/EW-RegionCalculations.gif)
<sub>Note: the version on the image may not reflect the latest version of Earthwork Tool.</sub>

## Advanced Region Features

### Multiple Region Management

Add and manage multiple regions in a single calculation:

1. **Add First Region**
   - Select initial region boundary
   - Configure surfaces and stripping
   - Execute initial calculation

2. **Add Additional Regions**
   - Click "Add" to include more regions
   - Select new region boundaries
   - Configure parameters for each region

3. **Remove Regions**
   - Select unwanted regions
   - Click "Remove" to delete from calculation
   - Totals update automatically

### Stripping Configuration

Configure topsoil stripping for each region:

- **Stripping Thickness** - Set depth of topsoil removal (e.g., 0.1m)
- **Region-Specific** - Different stripping depths per region
- **Calculation Impact** - Stripping affects final volume results
- **Validation** - Verify stripping calculations match expected values

### Validation and Verification

Use the tool to validate region calculations:

1. **Create Test Surface** - Generate stripping surface with known thickness
2. **Compare Surfaces** - Use full volume surface to compare existing vs. stripping
3. **Verify Results** - Check that calculated volumes match expected values
4. **Adjust Parameters** - Modify settings as needed for accuracy

## Workflow Examples

### Example 1: Single Region Calculation

1. **Click "Add Region Volume Surfaces"** in the main UI
2. **Select Region** - Choose a closed region boundary
3. **Configure Surfaces** - Set existing and proposed surfaces
4. **Add Stripping** (optional) - Set topsoil stripping thickness
5. **Execute Calculation** - Run the region analysis
6. **Review Results** - Check region-specific cut/fill volumes

### Example 2: Multiple Region Project

1. **Add First Region** - Configure initial region with surfaces
2. **Execute Calculation** - Run analysis for first region
3. **Add Second Region** - Include additional region boundary
4. **Configure Parameters** - Set surfaces and stripping for new region
5. **Update Calculation** - Re-run analysis for both regions
6. **Review Totals** - Check hierarchical totals and grand totals

### Example 3: Stripping Validation

1. **Create Stripping Surface** - Generate surface with 0.1m stripping
2. **Compare Surfaces** - Use full volume surface to compare existing vs. stripping
3. **Verify Calculation** - Check that region stripping matches full surface result
4. **Adjust Parameters** - Modify stripping depth if needed

## Best Practices

### Region Definition
- **Closed Boundaries** - Ensure regions are properly closed
- **Clear Boundaries** - Use well-defined region boundaries
- **Logical Grouping** - Group related areas into single regions
- **Descriptive Names** - Name regions clearly for easy identification

### Calculation Management
- **Start Simple** - Begin with single region calculations
- **Add Incrementally** - Add regions one at a time for better control
- **Validate Each Step** - Verify results after each region addition
- **Document Settings** - Keep records of region configurations

### Quality Assurance
- **Cross-Reference Results** - Compare with full volume surface calculations
- **Validate Totals** - Verify parent-child relationships are correct
- **Check Stripping** - Confirm stripping calculations are accurate
- **Review Hierarchical Structure** - Ensure totals update correctly 
