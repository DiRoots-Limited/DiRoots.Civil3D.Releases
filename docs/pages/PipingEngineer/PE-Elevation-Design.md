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

Piping Engineer provides advanced elevation design capabilities with auto-edition mode that includes hold reference options and automatic flow direction adjustments.


## Overview

Elevation design allows you to:
- Control piping network elevations with multiple reference strategies
- Automatically adjust upstream/downstream pipes based on flow direction
- Maintain system integrity during elevation modifications



## Elevation Design Cases

By modifying the 'Slope', 'Start Invert Elevation', 'End Invert Elevation' and using the Edition inputs of 'Hold Reference' and 'Auto flow Edition', the user can design easilly their pipes in elevation. The following cases are listed below. 

### Pipe Highest Point

Use the highest point of the entire system as a reference:

- **Select pipes** flowing in the same direction that need adjustment
- **Hold the highest point** of the system as reference
- **Adjust slopes** on specific pipes while maintaining system integrity
- **Apply changes** with automatic downstream adjustments

> **GIF Placeholder:** Demonstrate highest point reference usage

### Pipe Lowest Point

Use the lowest point of the system as a reference:

- **Hold the lowest point** as the reference elevation
- **Modify upstream branches** automatically
- **Maintain original slopes** for unmodified pipes
- **Adjust connected elements** based on flow direction

> **GIF Placeholder:** Show lowest point reference usage

### Pipe Start and Pipe End

Handle different pipe drawing directions in Civil 3D:

- **Pipe Start** - Reference the starting point of the pipe
- **Pipe End** - Reference the ending point of the pipe
- **Flexible reference** based on how pipes were originally drawn
- **User-defined reference** selection

> **GIF Placeholder:** Demonstrate start/end reference options

### Hold Slope

Maintain existing slopes while adjusting elevations:

- **Disable slope modification** - Only elevation values can be changed
- **Move entire system** while preserving slopes
- **Adjust start/end elevations** to shift the system
- **Maintain slope relationships** throughout the network

> **GIF Placeholder:** Show hold slope functionality

## Auto-Flow Edition Modes

### All Branches Downstream

Automatically adjust all downstream pipes when modifying elevations:

- **Modify selected pipes** with new slope or elevation values
- **Automatically adjust** all connected downstream pipes
- **Maintain flow direction** and system connectivity
- **Preserve original slopes** for unmodified upstream pipes

> **GIF Placeholder:** Demonstrate downstream adjustment mode

### All Branches Upstream

Automatically adjust all upstream pipes when modifying elevations:

- **Modify selected pipes** with new slope or elevation values
- **Automatically adjust** all connected upstream pipes
- **Maintain flow direction** and system connectivity
- **Preserve original slopes** for unmodified downstream pipes

> **GIF Placeholder:** Show upstream adjustment mode

### Only Selection

Modify only the specifically selected pipes:

- **No automatic adjustments** to upstream or downstream pipes
- **Modify only selected elements** without affecting the rest of the system
- **Maintain system integrity** for unselected pipes
- **Precise control** over individual pipe modifications

> **GIF Placeholder:** Demonstrate selection-only mode


## Workflow Examples

### Adjusting Multiple Pipes from Highest Point

1. **Select pipes** flowing in the same direction that need adjustment
2. **Choose "Pipe Highest Point"** as hold reference
3. **Set auto-flow edition** to "All Branches Downstream"
4. **Enter new slope** (e.g., 3%)
5. **Apply changes** - system adjusts selected pipes and all downstream pipes

> **GIF Placeholder:** Demonstrate complete workflow example

### Moving System Down While Preserving Slopes

1. **Select pipes** to modify
2. **Choose "Hold Slope"** as reference option
3. **Set auto-flow edition** to "All Branches Downstream"
4. **Modify elevation** (e.g., from 2m to 1m - moving system down 1 meter)
5. **Apply changes** - entire system moves down while preserving all slopes

> **GIF Placeholder:** Show slope preservation workflow

### Single Pipe Adjustment

1. **Select specific pipe** to modify
2. **Choose "Only Selection"** for auto-flow edition
3. **Modify elevation** or slope as needed
4. **Apply changes** - only the selected pipe is modified

> **GIF Placeholder:** Demonstrate single pipe adjustment


