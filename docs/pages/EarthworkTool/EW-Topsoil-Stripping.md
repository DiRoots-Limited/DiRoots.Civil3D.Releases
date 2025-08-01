---
layout: default
title: Topsoil Stripping
parent: Earthwork Tool User Guide
nav_order: 3
---

# Topsoil Stripping
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Topsoil Stripping

The Earthwork Tool provides comprehensive topsoil stripping capabilities, allowing you to create stripping surfaces and configure stripping parameters for accurate earthwork calculations. This feature integrates seamlessly with region-based calculations.

## Overview

Topsoil stripping is essential for accurate earthwork calculations, as topsoil is often removed and stockpiled before grading begins. The Earthwork Tool allows you to configure stripping thickness for regions and validate stripping calculations against full surface comparisons.

## Stripping Configuration

### Region-Based Stripping

Configure topsoil stripping within region calculations:

1. **Select Region**
   - Choose a defined region for stripping configuration
   - Ensure region is properly closed for accurate calculations

2. **Configure Stripping**
   - Set stripping thickness (e.g., 0.1m, 0.2m)
   - Configure stripping parameters for the specific region
   - Stripping affects the final volume calculations

3. **Execute Calculation**
   - Run the region analysis with stripping included
   - View stripping volumes in the calculation results
   - Check hierarchical totals including stripping

### Stripping Thickness Configuration

Set appropriate stripping depths for different project requirements:

- **Standard Stripping** - Common depths (0.1m to 0.3m)
- **Project-Specific** - Custom depths based on site conditions
- **Region-Variable** - Different stripping depths per region
- **Validation** - Verify stripping calculations are accurate

## Validation and Verification

### Stripping Surface Validation

Use the tool to validate stripping calculations:

1. **Create Test Surface**
   - Generate a stripping surface with known thickness
   - Use the stripping configuration to create a new surface

2. **Compare with Full Volume**
   - Use full volume surface to compare existing vs. stripping surface
   - Verify that calculated volumes match expected values

3. **Cross-Reference Results**
   - Compare region stripping results with full surface results
   - Ensure consistency between different calculation methods

### Example Validation Process

1. **Configure Stripping**
   - Set stripping thickness to 0.1m in region calculation
   - Execute region calculation with stripping

2. **Create Stripping Surface**
   - Generate a new surface with 0.1m stripping from existing surface
   - Use this as a separate surface for comparison

3. **Full Volume Comparison**
   - Use full volume surface to compare existing vs. stripping surface
   - Verify that results match the region stripping calculation

4. **Adjust Parameters**
   - Modify stripping thickness if needed
   - Re-run calculations to verify accuracy

## Integration with Region Calculations

### Hierarchical Structure

Stripping calculations integrate with the hierarchical calculation system:

#### Child Elements
- **Individual Region Stripping** - Stripping volumes per region
- **Stripping Thickness** - Configured depth for each region
- **Surface Comparisons** - Region-specific stripping analysis

#### Parent Totals
- **Stripping Totals** - Sum of all region stripping volumes
- **Combined Results** - Stripping included in overall calculations
- **Automatic Updates** - Totals update when stripping parameters change

### Multiple Region Stripping

Configure different stripping depths for multiple regions:

1. **First Region**
   - Set stripping thickness (e.g., 0.1m)
   - Configure surfaces and execute calculation

2. **Additional Regions**
   - Add more regions with different stripping depths
   - Configure stripping parameters for each region
   - View combined results in hierarchical totals

3. **Total Stripping**
   - Review total stripping volumes across all regions
   - Verify calculations match expected values

## Advanced Features

### Dynamic Stripping Adjustment

Modify stripping parameters and see immediate results:

- **Real-time Updates** - Calculations update when stripping changes
- **Parameter Validation** - Verify stripping settings are appropriate
- **Result Verification** - Check that changes produce expected results
- **Quality Control** - Ensure stripping calculations are accurate

### Stripping Surface Creation

Generate dedicated stripping surfaces for analysis:

- **Surface Generation** - Create new surfaces with stripping applied
- **Comparison Analysis** - Use stripping surfaces in full volume calculations
- **Validation Tool** - Verify stripping calculations are correct
- **Documentation** - Maintain stripping surfaces for project records

## Workflow Examples

### Example 1: Basic Stripping Configuration

1. **Add Region Volume Surfaces** in the main UI
2. **Select Region** - Choose a closed region boundary
3. **Configure Surfaces** - Set existing and proposed surfaces
4. **Add Stripping** - Set topsoil stripping thickness (e.g., 0.1m)
5. **Execute Calculation** - Run analysis with stripping included
6. **Review Results** - Check stripping volumes and totals

### Example 2: Stripping Validation

1. **Create Stripping Surface** - Generate surface with 0.1m stripping
2. **Full Volume Comparison** - Compare existing vs. stripping surface
3. **Verify Results** - Check that volumes match region stripping
4. **Adjust Parameters** - Modify stripping depth if needed

### Example 3: Multiple Region Stripping

1. **Configure First Region** - Set stripping for initial region
2. **Add Second Region** - Include additional region with different stripping
3. **Execute Calculations** - Run analysis for both regions
4. **Review Totals** - Check combined stripping volumes

## Best Practices

### Stripping Configuration
- **Site-Specific** - Base stripping depth on site conditions
- **Project Requirements** - Consider project specifications
- **Validation** - Always verify stripping calculations
- **Documentation** - Record stripping parameters and results

### Quality Assurance
- **Cross-Reference** - Compare with full surface calculations
- **Validation Testing** - Use test surfaces to verify accuracy
- **Parameter Review** - Check stripping settings are appropriate
- **Result Verification** - Ensure calculations match expectations

### Workflow Optimization
- **Start Simple** - Begin with basic stripping configuration
- **Incremental Testing** - Test stripping parameters step by step
- **Validation Process** - Establish validation workflow
- **Documentation** - Keep records of stripping configurations 
