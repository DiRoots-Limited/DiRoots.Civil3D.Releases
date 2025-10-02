---
layout: default
title: Object Inspection
parent: Template Inspector User Guide
nav_order: 3
---

# Object Inspection
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Object Inspection

Template Inspector provides comprehensive object inspection and depth scanning capabilities to examine object properties, usage, and dependencies in detail. The depth scan feature performs comprehensive scans to find object usage and dependencies throughout your settings and objects, providing detailed information about where inspected objects are used.

## Overview

Object inspection and depth scanning allows you to:
- Examine object properties and settings
- View detailed usage information
- Analyze object dependencies
- Understand object relationships
- Find all instances where objects are used
- Discover hidden dependencies and references
- Analyze object usage patterns
- Identify unused objects for cleanup

> **GIF Placeholder:** Show overview of object inspection and depth scan interface

### Object Types Supported
- **Layers** - Inspect layer usage and associated objects
- **Line Types** - Find line type assignments and usage
- **Dimension Styles** - Check dimension style usage
- **Hatch Styles** - Locate hatch pattern usage
- **Text Styles** - Find text style assignments


## Scan Types

### Object Usage Scan

Scan for object usage throughout drawings:

- **Created Objects Check** - Check all created objects in the drawing
- **Settings with Object Assignment** - Find all settings with objects assigned to them
- **Dependent Objects List** - List all dependent objects and their relationships
- **Usage Detection** - Find all places where objects are used
- **Reference Discovery** - Discover object references and dependencies

> **GIF Placeholder:** Demonstrate object usage scanning

## Inspection Interface

### Four-Column Display

The inspector finds objects that reference the objects being inspected. View inspection results in organized format with four columns:

1. **Template Component Column** - Shows the settings path where the settings use the object
2. **Associated Object Column** - Shows objects that are created in the drawing that have the inspected object referenced inside their properties
3. **Assigned Object Column** - Shows the assigned object that can be modified
4. **Count Column** - Lists the number of instances that have the object assigned

> **GIF Placeholder:** Show four-column display interface



## Inspection Workflow

### Object Selection

Select objects for inspection:

1. **Choose Object Type** - Select the type of object to inspect
2. **Search for Objects** - Search for specific objects
3. **Select Target Object** - Select the object to inspect
4. **Begin Inspection** - Start the inspection process

> **GIF Placeholder:** Demonstrate object selection workflow

### Inspection Process

Conduct comprehensive inspection:

1. **Load Object Data** - Load object data and properties
2. **Analyze Properties** - Analyze object properties
3. **Check Usage** - Check object usage
4. **Examine Dependencies** - Examine object dependencies
5. **Review Results** - Review inspection results

> **GIF Placeholder:** Show complete inspection process

## Usage Display

Template Inspector shows usage display capabilities to show how objects are used throughout your drawings, including detailed usage counts, locations, and patterns. The usage count specifically tracks only the objects that are placed or created in the drawing.

### Usage Display Overview

Usage display allows you to:
- View detailed usage information for objects
- See usage counts and patterns
- Analyze usage distribution

> **GIF Placeholder:** Show overview of usage display interface

### Usage Count Display

View usage count information:

- **Total Usage** - Total number of times objects are placed or created in the drawing

> **GIF Placeholder:** Demonstrate usage count display

### Usage Display Interface

#### Four-Column Layout

View usage information in organized format:

- **Template Component** - Shows the settings path where the settings use the object
- **Associated Object** - Shows objects that are created in the drawing that have the inspected object referenced inside their properties
- **Assigned Object** - Shows the assigned object that can be modified
- **Count** - Displays usage count information for placed/created objects only

> **GIF Placeholder:** Show four-column layout interface

## Component Column Reference

The **Template Component column** identifies the Settings location from the Civil 3D object in the tree structure, making it easy to locate.

### Component Path Structure

**Example Component Path for Layer:**
```
Alignment Styles/Roadway Centerline Alignment Proposed - ATG/Display/Plan/Line
```
> **GIF Placeholder:** Show the path in the tool and find the same setting in the C3D structure.

## Missing Object Limitations

Due to current Civil 3D API limitations, Template Inspector cannot collect if data is associated to the following:

- **Section View Styles** - Drafting buffer outline
- **Rail Turnout** - All rail turnout objects
- **Can't View Styles** - Equilibrium can't line annotation, Applied cant line annotation
- **Bridge Styles** - All bridge related styles

The previous mentioned limitations are imposed by the Civil 3D API and are not within the control of Template Inspector. We continue to monitor API updates and will add support for these styles when they become available through the Civil 3D API.
