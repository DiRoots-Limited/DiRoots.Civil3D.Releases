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

Piping Engineer provides elevation design capabilities with auto-edition mode that includes hold reference options and automatic flow direction adjustments. The tool helps to edit the network system while offering  control over pipe elevations and slopes.

## Overview

The Elevation Design feature enables control over piping network elevations with new system edition capabilities:

- **Hold Reference Options** - Multiple reference point strategies
- **Auto-Flow Edition** - Automatic upstream/downstream adjustments
- **System-aware elevation calculations**
- **Slope validation** and optimization
- **Flexible modification modes**

## Hold Reference Options

Piping Engineer offers several hold reference strategies to maintain system integrity during elevation modifications:

### Pipe Highest Point

Use the highest point of the entire system as a reference:

- **Select pipes** flowing in the same direction that need adjustment
- **Hold the highest point** of the system as reference
- **Adjust slopes** on specific pipes while maintaining system integrity
- **Apply changes** with automatic downstream adjustments

**Use Case**: When pipes are not working correctly and you need to adjust slopes while keeping the highest point fixed.

### Pipe Lowest Point

Use the lowest point of the system as a reference:

- **Hold the lowest point** as the reference elevation
- **Modify upstream branches** automatically
- **Maintain original slopes** for unmodified pipes
- **Adjust connected elements** based on flow direction

**Use Case**: When you need to adjust the system from the lowest point upward.

### Pipe Start and Pipe End

Handle different pipe drawing directions in Civil 3D:

- **Pipe Start** - Reference the starting point of the pipe
- **Pipe End** - Reference the ending point of the pipe
- **Flexible reference** based on how pipes were originally drawn
- **User-defined reference** selection

**Note**: In Civil 3D, pipes can be drawn from lower to higher points or higher to lower points. This option allows users to choose the appropriate reference based on their specific drawing method.

### Hold Slope

Maintain existing slopes while adjusting elevations:

- **Disable slope modification** - Only elevation values can be changed
- **Move entire system** while preserving slopes
- **Adjust start/end elevations** to shift the system
- **Maintain slope relationships** throughout the network

**Use Case**: When you need to move the entire system up or down while keeping all existing slopes intact.

## Auto-Flow Edition Modes

### All Branches Downstream

Automatically adjust all downstream pipes when modifying elevations:

- **Modify selected pipes** with new slope or elevation values
- **Automatically adjust** all connected downstream pipes
- **Maintain flow direction** and system connectivity
- **Preserve original slopes** for unmodified upstream pipes

**Example**: When editing a pipe to 4% slope, all downstream pipes are automatically adjusted while upstream pipes remain unchanged.

### All Branches Upstream

Automatically adjust all upstream pipes when modifying elevations:

- **Modify selected pipes** with new slope or elevation values
- **Automatically adjust** all connected upstream pipes
- **Maintain flow direction** and system connectivity
- **Preserve original slopes** for unmodified downstream pipes

**Example**: When editing the lowest point of a system, all upstream branches are automatically modified to maintain proper flow.

### Only Selection

Modify only the specifically selected pipes:

- **No automatic adjustments** to upstream or downstream pipes
- **Modify only selected elements** without affecting the rest of the system
- **Maintain system integrity** for unselected pipes
- **Precise control** over individual pipe modifications

**Use Case**: When you want to adjust specific pipes without affecting the connected network.

## Practical Examples

### Example 1: Adjusting Multiple Pipes from Highest Point

1. **Select pipes** flowing in the same direction that need adjustment
2. **Choose "Pipe Highest Point"** as hold reference
3. **Set auto-flow edition** to "All Branches Downstream"
4. **Enter new slope** (e.g., 3%)
5. **Apply changes** - system adjusts selected pipes and all downstream pipes

### Example 2: Moving System Down While Preserving Slopes

1. **Select pipes** to modify
2. **Choose "Hold Slope"** as reference option
3. **Set auto-flow edition** to "All Branches Downstream"
4. **Modify elevation** (e.g., from 2m to 1m - moving system down 1 meter)
5. **Apply changes** - entire system moves down while preserving all slopes

### Example 3: Single Pipe Adjustment

1. **Select specific pipe** to modify
2. **Choose "Only Selection"** for auto-flow edition
3. **Modify elevation** or slope as needed
4. **Apply changes** - only the selected pipe is modified

## Workflow Tips

### Data Management

- **Reload data** after undo/redo operations to ensure accurate information
- **Refresh UI** when switching between different modification modes
- **Verify selections** before applying changes to avoid unintended modifications

### Testing and Validation

- **Record short videos** when testing to help identify specific issues
- **Test different scenarios** to understand how each mode behaves
- **Verify system integrity** after modifications
- **Check slope compliance** with system requirements

### Best Practices

- **Start with small modifications** to understand the tool's behavior
- **Use appropriate reference points** based on your design intent
- **Consider flow direction** when choosing auto-flow edition modes
- **Test modifications** on copies before applying to production designs

## System Integration

### Civil 3D Compatibility

The tool integrates seamlessly with Civil 3D piping networks:

- **Native Civil 3D objects** - works with existing pipe networks
- **Flow direction awareness** - understands Civil 3D flow direction
- **Drawing method flexibility** - accommodates different pipe drawing approaches
- **Real-time updates** - modifications reflect immediately in Civil 3D

### Error Handling

- **Validation checks** before applying modifications
- **Conflict detection** for incompatible changes
- **Rollback capability** for problematic modifications
- **User feedback** for successful and failed operations

## Advanced Features

### Bulk Operations

- **Multiple pipe selection** for simultaneous modifications
- **Network-wide adjustments** with single operation
- **Batch processing** for large networks
- **Consistent application** across selected elements

### Customization

- **User-defined reference points** for specific project needs
- **Custom slope constraints** based on project requirements
- **Flexible modification strategies** for complex networks
- **Project-specific workflows** and settings 
