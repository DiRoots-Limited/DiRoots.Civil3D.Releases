---
layout: default
title: Station Management
parent: Grading Pro User Guide
nav_order: 2
---

# Station Management
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Station Management

Grading Pro provides comprehensive station management capabilities, allowing you to define where sections will be placed along your reference path. The tool supports both individual station placement and range-based station generation for efficient grading design.

## Overview

Stations define the locations where grading sections are applied along your reference path (alignment or corridor). Grading Pro offers flexible station definition methods to accommodate various project requirements and design scenarios.

## Station Definition Methods

### Individual Stations

Define specific station locations for precise control:

- **Exact Location** - Specify exact station values along the path
- **Side Selection** - Choose left, right, or both sides for section placement
- **Angle Control** - Define the angle of section placement (default: 90 degrees)
- **Custom Names** - Assign descriptive names to individual stations

**Example Individual Stations:**
- Station 20: Left side, 90 degrees
- Station 40: Right side, 90 degrees
- Station 60: Both sides, 45 degrees

### Range of Stations

Generate multiple stations automatically using range parameters:

- **Start Station** - Beginning station value
- **End Station** - Ending station value
- **Interval** - Distance between stations (e.g., 10 meters)
- **Side and Angle** - Applied to all stations in the range

**Example Range Configuration:**
- Start: 50m
- End: 120m
- Interval: 10m
- Result: Stations at 50, 60, 70, 80, 90, 100, 110, 120m

### Mixed Approach

Combine individual and range-based stations for complex scenarios:

- **Individual Stations** - For critical locations requiring specific attention
- **Range Stations** - For areas requiring consistent spacing
- **Flexible Combination** - Mix both methods as needed

## Creating Station Configurations

### Step-by-Step Process

1. **Access Station Configuration**
   - Click the configuration button in the main UI
   - Navigate to the "Station Configuration" tab

2. **Create New Station Group**
   - Click "New" to create a new station configuration
   - Assign a descriptive name (e.g., "Main Road Stations")

3. **Add Individual Stations**
   - Click "Individually" to add specific stations
   - Enter station value (e.g., 20, 40, 60)
   - Select side (Left, Right, Both)
   - Set angle (default: 90 degrees)

4. **Add Range of Stations**
   - Click "Range" to add multiple stations
   - Enter start station (e.g., 50)
   - Enter end station (e.g., 120)
   - Set interval (e.g., 10 meters)
   - Configure side and angle settings

5. **Save Configuration**
   - Save the station configuration for use in grading types

### Station Management Features

#### Adding Stations
- **Individual Addition** - Add specific stations one by one
- **Range Addition** - Generate multiple stations with defined parameters
- **Flexible Parameters** - Customize side and angle for each station type

#### Duplicating Stations
- **Select and Duplicate** - Copy existing station configurations
- **Modify Duplicates** - Adjust parameters for the new configuration
- **Efficient Workflow** - Save time by duplicating and modifying

#### Removing Stations
- **Individual Removal** - Delete specific stations from the configuration
- **Bulk Removal** - Remove multiple stations simultaneously
- **Range Adjustment** - Modify range parameters to exclude specific areas

## Side and Angle Configuration

### Side Selection Options

- **Left Side** - Place sections on the left side of the path
- **Right Side** - Place sections on the right side of the path
- **Both Sides** - Place sections on both sides simultaneously

### Angle Settings

- **Default Angle** - 90 degrees (perpendicular to path)
- **Custom Angles** - Specify any angle for section placement
- **Angle Impact** - Affects how sections are oriented relative to the path

**Common Angle Applications:**
- 90° - Standard perpendicular placement
- 45° - Angled placement for specific design requirements
- Custom angles - For complex geometric requirements

## Advanced Station Techniques

### Station Spacing Strategies

#### Uniform Spacing
- **Consistent Intervals** - Use regular spacing (e.g., every 10m)
- **Predictable Results** - Easy to plan and implement
- **Standard Applications** - Suitable for most grading scenarios

#### Variable Spacing
- **Critical Areas** - Closer spacing in important locations
- **Transition Zones** - Gradual spacing changes
- **Custom Requirements** - Project-specific spacing needs

### Station Optimization

#### Efficiency Considerations
- **Minimum Spacing** - Avoid stations too close together
- **Maximum Spacing** - Ensure adequate coverage
- **Critical Points** - Place stations at key geometric changes

#### Quality Control
- **Station Verification** - Check station placement before application
- **Spacing Validation** - Ensure appropriate intervals
- **Coverage Analysis** - Verify all areas are adequately covered

## Integration with Grading Types

### Station-Section Combination

Stations are combined with sections in grading types:

1. **Select Stations** - Choose from available station configurations
2. **Select Sections** - Choose from available section configurations
3. **Create Grading Type** - Combine stations and sections
4. **Apply to Surface** - Use the grading type to modify surfaces

### Multiple Grading Types

- **Different Station Sets** - Use different stations for different areas
- **Section Variations** - Apply different sections to different stations
- **Complex Scenarios** - Combine multiple grading types for complex projects

## Best Practices

### Station Planning
- **Project Requirements** - Align stations with project needs
- **Geometric Changes** - Place stations at key geometric points
- **Design Intent** - Ensure stations support design objectives
- **Efficiency** - Balance coverage with computational efficiency

### Configuration Management
- **Descriptive Names** - Use clear names for station configurations
- **Documentation** - Document station purposes and applications
- **Version Control** - Maintain different versions for different scenarios
- **Testing** - Verify station configurations before large-scale application

### Workflow Optimization
- **Template Creation** - Create reusable station templates
- **Standard Configurations** - Develop standard station sets for common scenarios
- **Efficient Setup** - Use range-based stations for large areas
- **Quality Assurance** - Review station placement for accuracy and completeness 
