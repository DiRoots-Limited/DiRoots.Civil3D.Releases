---
layout: default
title: Calculations
parent: Earthwork Tool User Guide
nav_order: 1
---

# Calculations
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Calculations

The Earthwork Tool provides comprehensive calculation capabilities for cut and fill analysis with both full surface comparisons and region-based calculations.

## Overview

The tool offers two main calculation approaches:
- **Full Surface Calculation** - Complete calculation comparison across entire surfaces
- **Region Volume Surfaces** - Region-specific calculations with defined boundaries
- **Hierarchical Totals** - Automatic calculation of parent and grand totals
- **Type Column** - Shows calculation type: Full surface comparison, Parent region, or Child region

> **GIF Placeholder:** Show overview of calculation capabilities

## Full Surface Calculation

The Earthwork Tool provides comprehensive surface comparison capabilities for calculating cut and fill volumes across entire project areas.

### Overview

Full surface calculation allows you to:
- Calculate cut and fill quantities by comparing two surfaces across the entire project area
- Use the same calculation methods as Civil 3D's dashboard feature
- Ensure consistency and accuracy in earthwork calculations
- Generate comprehensive volume analysis results

> **GIF Placeholder:** Show overview of full surface calculation capabilities

### Full Volume Surface Workflow

#### Accessing the Feature

1. **Open Earthwork Tool** from the DiRoots tab
2. **Main UI** - The tool displays the main interface with calculation options
3. **Add Full Volume Surface** - Click this option to create a new full volume calculation

> **GIF Placeholder:** Demonstrate accessing the full volume surface feature

#### Surface Selection Process

1. **Select Existing Surface**
   - Choose the current ground surface from available surfaces
   - This represents the existing conditions before construction

2. **Select Proposed/Future Surface**
   - Choose the proposed or future ground surface
   - This represents the final design conditions

3. **Execute Calculation**
   - Click the execute button to run the comparison
   - The tool performs the same calculations as Civil 3D dashboard

> **GIF Placeholder:** Show surface selection process

#### Calculation Results

The tool provides comprehensive volume analysis:

- **Cut Volume** - Total volume of material to be removed
- **Fill Volume** - Total volume of material to be added
- **Net Volume** - Difference between cut and fill
- **Unit Display** - Results shown in selected units (m³, yd³, ft³, acre-ft)

> **GIF Placeholder:** Demonstrate calculation results display


## Region Calculations

The Earthwork Tool provides region-based volume calculations with defined boundaries for precise earthwork analysis in specific project areas.

### Overview

Region calculations allow you to:
- Calculate volumes for specific areas using defined boundaries
- Support multiple regions for phased construction
- Maintain hierarchical relationships with automatic totals
- Configure topsoil stripping per region

> **GIF Placeholder:** Show overview of region calculations capabilities

### Region Volume Surfaces

#### Creating Region Calculations

1. **Access Region Feature**
   - Click "Add Region Volume Surfaces" in the main UI
   - Select defined regions for calculation boundaries
   - Configure surfaces for each region

2. **Region Selection**
   - Choose closed regions that define calculation boundaries
   - Ensure regions are properly closed and valid
   - Select appropriate regions for your analysis

> **GIF Placeholder:** Demonstrate creating region calculations

#### Multiple Region Support

Support for multiple regions:

- **Individual Regions** - Calculate volumes for each region separately
- **Phased Construction** - Support construction phasing with multiple regions
- **Region Organization** - Organize regions logically for project needs
- **Hierarchical Results** - Maintain parent-child relationships

> **GIF Placeholder:** Show multiple region support

#### Hierarchical Calculations

- **Child Elements** - Individual region calculations
- **Parent Totals** - Sum of all child elements within a region
- **Grand Totals** - Sum of full volume surface and all region volume surfaces
- **Total Updates** - Totals update automatically when calculations are executed

### Parent-Child Region Workflow

The region workflow combines parent and child regions to create a hierarchical calculation system where parent regions group multiple child regions and provide child group totals.

### Creating Parent Regions

1. **Access Parent Region Feature**
   - Click "Add Region Volume Surfaces" in main UI

2. **Parent Region Configuration**
   - Set parent region name and description
   - Assign existing and proposed surfaces
   - Configure topsoil stripping thickness for entire parent group

3. **Child Region Management**
   - Add multiple child regions under parent
   - Each child will inherit stripping depth configuration from the parent
   - Parent calculates totals from all children

### Creating Child Regions

1. **Access Child Region Feature**
   - Select parent and Click "Add Surface Region" (Children Region). (or Right click on the parent region row in the table and click on 'Add Surface Region')
   - Select closed region boundaries
   - Configure individual region settings

2. **Child Region Configuration**
   - Set region name and description
   - Each child inherits the existing and proposed surfaces and stripping thickness from the parent
   - Set the subgrade base depth for this specific child region

3. **Individual Calculations**
   - Each child region calculates independently
   - Results include cut/fill volumes with stripping consideration
   - Type column shows "Child Region" for identification

### Integrated Workflow Example: Construction Phasing

**Parent Region: "Phase 1 Construction"**
- Stripping thickness: 0.15m (applies to all children)
- Existing surface: "Existing_Ground"
- Proposed surface: "Phase1_Design"

- **Child Region 1: "Building Pad A"**
  - Subgrade base depth: 0.30m
  - Inherits: Stripping thickness 0.15m, Existing surface, Proposed surface
  - Results: Cut: 2,500 m³, Fill: 1,800 m³, Net: 700 m³ cut

- **Child Region 2: "Building Pad B"**
  - Subgrade base depth: 0.25m
  - Inherits: Stripping thickness 0.15m, Existing surface, Proposed surface
  - Results: Cut: 3,200 m³, Fill: 2,100 m³, Net: 1,100 m³ cut

- **Child Region 3: "Parking Area"**
  - Subgrade base depth: 0.20m
  - Inherits: Stripping thickness 0.15m, Existing surface, Proposed surface
  - Results: Cut: 1,500 m³, Fill: 2,200 m³, Net: 700 m³ fill

**Parent Region Totals :**
- Total Cut: 7,200 m³
- Total Fill: 6,100 m³
- Net: 1,100 m³ cut


> **GIF Placeholder:** Show integrated parent-child region creation and management workflow

## Totals Description

The tool maintains hierarchical totals that automatically update when calculations are executed.

### Total Hierarchy

   - Sum of full volume surface and parent region volume surfaces
   - Project-wide earthwork balance
   - Includes all stripping and subgrade considerations

## Best Practices

- **Verify Region Boundaries** - Ensure regions are properly closed
- **Check Surface Assignment** - Verify correct surfaces are assigned to regions
- **Plan Region Hierarchy** - Plan parent-child relationships logically
- **Use Descriptive Names** - Name regions clearly for easy identification
