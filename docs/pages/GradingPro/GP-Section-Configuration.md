---
layout: default
title: Section Setup
parent: Grading Pro User Guide
nav_order: 3
---

# Section Setup
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Section Setup

Grading Pro provides a section setup capability with multiple definition methods for precise grading design.

## Overview

Section configuration allows you to:
- Create Section types that can be reused across projects.
- Define sections using multiple methods (distance with offset, distance with slope, offset with slope, slope to surface)
- Setup section points efficiently with add, remove, and reorder capabilities
- Shows each point location on the section view.
- Add feature lines as objects in your section definitions for greater control and flexibility

## Manage Sections

### Creating, Duplicating and Removing

Manage your Section list by creating new, duplicating and removing new types

> **GIF Placeholder:** Demonstrate section list management buttons

## Definition Methods

### Distance with Offset

Define a Feature Line point based on distance and offset:

- **Distance** - Specify distance from the previous point or origin
- **Height/Offset** - Specify offset values from the previous point or origin

> **GIF Placeholder:** Demonstrate distance with offset method

### Distance with Slope

Define a Feature Line point based on distance and slope:

- **Distance** - Specify distance from the previous point or origin
- **Slope Percentage** - Specify slope percentage for point or origin

> **GIF Placeholder:** Show distance with slope method

### Offset with Slope

Define a Feature Line points by offset and slope:

- **Height/Offset** - Specify offset values from the previous point or origin
- **Slope Percentage** - Specify slope percentage for point elevation


> **GIF Placeholder:** Demonstrate offset with slope method

### Slope to Surface

Define points by slope from the previous point projected to the selected surface:

- **Offset from Path** - Specify offset distance from the reference path
- **Slope Percentage** - Specify slope percentage for point elevation

> **GIF Placeholder:** Demonstrate offset with slope method

## Point Management

### First Point

- The first point could be placed on the origin (0, 0) or at a distance offset from the origin.

> **GIF Placeholder:** Show point addition process

### Adding Points

Add points to section setups:

> **GIF Placeholder:** Show point addition process

### Removing Points

Remove points from section setups:

> **GIF Placeholder:** Demonstrate point removal

### Reordering Points

Reorder points in section definitions:

> **GIF Placeholder:** Show point reordering

## Object Feature Line Integration

Grading Pro allows you to add feature lines as objects in your section definitions, providing greater control and flexibility in grading design.

### Overview

Feature line integration enables you to:
- Use existing feature lines, platforms, or other geometric objects as part of your section definitions
- Maintain exact geometry from existing designs while incorporating them into new grading scenarios
- Achieve precise control over complex geometric forms
- Ensure design consistency with existing elements

> **GIF Placeholder:** Show overview of feature line integration capabilities

### Adding Object Feature Lines into Sections

Follow these steps to add feature lines to your section definitions:

1. **Open Section Configuration**  
   Go to the "Section Configuration" tab within Grading Pro.

2. **Add Feature Lines**  
   Click the "Object Feature Lines" button to begin the integration process.

3. **Select Feature Lines or Objects**  
   Choose the feature lines, platforms, or other geometric objects you want to include in your section.

4. **Specify Origin Point**  
   Select where the feature line will connect to the section. You can choose the midpoint, an endpoint, or a custom point along the feature line. The origin point determines how the feature line is positioned within the section.

5. **Set Orientation and Placement**  
   Define the orientation by selecting which end or direction the feature line should follow. Adjust rotation or placement as needed to ensure the feature line aligns correctly with your section design.

> **GIF Placeholder:** Demonstrate the full process of integrating a feature line, including origin point selection and orientation control.

### Applications

Feature line integration supports various grading design scenarios:

- **Platform Integration** - Incorporate platform feature lines by selecting the defining lines, specifying connection points, setting proper orientation, and applying them to section definitions
- **Complex Geometry Integration** - Use existing feature lines from previous designs to maintain exact geometry, integrate intricate shapes, and ensure design consistency across projects
- **Reusable Objects** - Create standard feature line elements that can be applied across multiple sections, saving time while maintaining consistent design quality and workflow efficiency
