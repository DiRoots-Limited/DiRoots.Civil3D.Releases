---
layout: default
title: Section Configuration
parent: Grading Pro User Guide
nav_order: 1
---

# Section Configuration
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Section Configuration

Grading Pro provides comprehensive section configuration capabilities with multiple definition methods, allowing you to create precise grading sections that can be reused across different projects.

## Overview

Section configuration is the core of Grading Pro's functionality, enabling you to define how surfaces will be modified. The tool offers three main definition methods and flexible point management to create complex grading scenarios.

## Section Definition Methods

### Distance with Offset Method

Define section points by specifying distance from the path and offset values:

- **Distance** - How far along the section from the origin point
- **Offset** - Perpendicular distance from the path (positive or negative)
- **Origin Point** - Always starts at zero distance from the path

**Example Configuration:**
- Point 1: Distance = 0m, Offset = 0m (origin)
- Point 2: Distance = 20m, Offset = -0.5m (going down)
- Point 3: Distance = 40m, Offset = 0.5m (going up)

### Distance with Slope Method

Define section points by distance and slope percentage:

- **Distance** - How far along the section from the previous point
- **Slope** - Percentage slope (e.g., 100% = 45 degrees)
- **Automatic Height Calculation** - Tool calculates elevation based on slope

**Example Configuration:**
- Point 1: Distance = 0m (origin)
- Point 2: Distance = 1m, Slope = 100% (steep upward)
- Point 3: Distance = 5m, Slope = 30% (moderate upward)

### Offset with Slope Method

Define section points by offset and slope percentage:

- **Offset** - Perpendicular distance from the path
- **Slope** - Percentage slope from the previous point
- **Flexible Placement** - Can go back and forth from the path

**Example Configuration:**
- Point 1: Offset = 0m (origin)
- Point 2: Offset = -2m, Slope = -50% (going down and back)
- Point 3: Offset = 0.5m, Slope = 30% (going up and forward)

## Creating Section Configurations

### Step-by-Step Process

1. **Access Configuration**
   - Click the configuration button in the main UI
   - Navigate to the "Section Configuration" tab

2. **Create New Section**
   - Click "New" to create a new section
   - Assign a descriptive name for easy identification

3. **Define Section Points**
   - Choose your preferred definition method
   - Add points using the selected method
   - Configure distance, offset, and/or slope values

4. **Manage Point Order**
   - Use up/down arrows to reorder points
   - Remember: points are defined relative to the previous point, not the origin

5. **Save Configuration**
   - Save the section for use in grading types

### Point Management Features

#### Adding Points
- **Add Point Button** - Insert new points into the section
- **Method Selection** - Choose definition method for each point
- **Value Entry** - Input distance, offset, and slope values

#### Removing Points
- **Remove Button** - Delete selected points from the section
- **Bulk Operations** - Remove multiple points simultaneously

#### Reordering Points
- **Up/Down Arrows** - Change the order of points in the section
- **Order Impact** - Point order affects the final section geometry
- **Relative Positioning** - Each point is positioned relative to the previous point

## Object Feature Line Integration

### Adding Feature Lines to Sections

1. **Select Feature Lines**
   - Click "Object Feature Lines" in the section configuration
   - Select existing feature lines from the drawing
   - Press Enter to confirm selection

2. **Define Origin Point**
   - Specify where the feature line connects to the section
   - Choose from available points (midpoint, endpoint, etc.)
   - This defines the placement location

3. **Set Orientation**
   - Define the rotation of the feature line object
   - Select endpoint to determine orientation
   - Adjust offset if needed

### Feature Line Applications

- **Platform Integration** - Add existing platforms to sections
- **Complex Geometry** - Incorporate detailed feature line geometry
- **Reusable Objects** - Use the same feature lines in multiple sections
- **Precise Control** - Maintain exact geometry from existing objects

## Advanced Section Techniques

### Channel Definition

Create drainage channels using negative slopes:

1. **Start with Origin** - Begin at the path (distance = 0, offset = 0)
2. **Go Down** - Use negative offset and slope to create channel bottom
3. **Go Up** - Use positive offset and slope to create channel sides
4. **Level Out** - Return to desired elevation

**Example Channel Section:**
- Point 1: Distance = 0m, Offset = 0m (origin)
- Point 2: Distance = 2m, Offset = -0.5m, Slope = -25% (going down)
- Point 3: Distance = 4m, Offset = 0.5m, Slope = 30% (going up)
- Point 4: Distance = 20m, Offset = 0.5m (level section)

### Complex Grading Scenarios

Combine multiple methods for complex sections:

- **Mixed Methods** - Use different definition methods for different points
- **Variable Slopes** - Adjust slopes based on terrain requirements
- **Multiple Levels** - Create terraced or stepped grading
- **Custom Geometry** - Design sections for specific project needs

## Best Practices

### Section Design
- **Start Simple** - Begin with basic sections and add complexity
- **Test Configurations** - Verify sections work as expected before applying
- **Use Descriptive Names** - Name sections clearly for easy identification
- **Document Intent** - Note the purpose and application of each section

### Point Management
- **Logical Order** - Arrange points in logical sequence
- **Consistent Methods** - Use consistent definition methods when possible
- **Validate Geometry** - Check that section geometry makes sense
- **Backup Configurations** - Save copies of working configurations

### Feature Line Integration
- **Select Appropriate Objects** - Choose feature lines that fit the section purpose
- **Verify Connections** - Ensure feature lines connect properly to sections
- **Test Integration** - Verify feature line placement before final application
- **Maintain Relationships** - Keep feature lines updated with section changes 
