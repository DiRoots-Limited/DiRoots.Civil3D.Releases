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

### Calculation Process

The full surface comparison calculates cut and fill volumes across the entire project area using the same methods as Civil 3D's dashboard feature.

1. **Surface Selection**
   - Choose existing ground surface (current conditions)
   - Select proposed/future surface (final design)
   - Execute comparison calculation

2. **Volume Analysis**
   - **Cut Volume** - Material to be removed
   - **Fill Volume** - Material to be added
   - **Net Volume** - Difference between cut and fill
   - **Unit Display** - Results in selected units (m³, yd³, ft³, acre-ft)


## Parent-Child Region Workflow

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
