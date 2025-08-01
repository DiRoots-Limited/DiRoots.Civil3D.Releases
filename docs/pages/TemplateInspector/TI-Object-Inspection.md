---
layout: default
title: Object Inspection
parent: Template Inspector User Guide
nav_order: 1
---

# Object Inspection
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Object Inspection

Template Inspector supports inspecting multiple object types to find where they are used in your files, helping you identify dependencies and make informed decisions about deletion or modification. The tool provides comprehensive search functionality and detailed inspection results.

## Overview

Object inspection is the core functionality of Template Inspector, allowing you to examine how objects are used throughout your files. The tool displays associated settings and objects, enabling you to understand dependencies and make informed decisions about object management.

## Supported Object Types

### Comprehensive Object Support

Template Inspector supports inspection of multiple object types:

- **Layers** - Inspect layer usage across all objects and styles
- **Line Types** - Find where line types are assigned
- **Hatch Styles** - Locate hatch pattern usage
- **Dimension Styles** - Check dimension style assignments
- **Text Styles** - Find text style usage throughout the file

### Object Selection Process

Choose which object type to inspect:

1. **Select Object Type** - Choose from layers, line types, dimension styles, hatch styles, text styles
2. **View Object List** - See all objects of the selected type
3. **Search Objects** - Use search functionality to find specific objects
4. **Filter Results** - Apply filters to narrow down results

## Search and Filter Functionality

### Search Capabilities

Find specific objects quickly using search:

- **Search by Name** - Search for objects by name or partial name
- **Real-time Results** - See results as you type
- **Case-insensitive** - Search works regardless of case
- **Partial Matching** - Find objects with partial name matches

### Example Search Usage

Search for specific objects:
- **Search "Section"** - Find all objects with "Section" in the name
- **Filter Results** - Narrow down results to specific categories
- **Quick Location** - Quickly locate objects in large datasets
- **Efficient Navigation** - Navigate through object lists efficiently

### Filtering Options

Filter data to focus on specific items:

- **Name-based Filtering** - Filter by object names
- **Category Filtering** - Filter by object categories
- **Usage Filtering** - Filter by usage status
- **Dynamic Filtering** - Apply multiple filter criteria simultaneously

## Inspection Results Display

### Two-Column Layout

The inspection interface displays results in a two-column format:

#### Settings Column
- **Associated Settings** - Shows all settings related to the selected object
- **Property Values** - Displays current property values
- **Configuration Details** - Shows detailed configuration information
- **Setting Relationships** - Displays relationships between settings

#### Objects Column
- **Associated Objects** - Lists all objects that use the selected item
- **Usage Count** - Shows number of associated objects
- **Object Types** - Displays types of associated objects
- **Object Details** - Shows detailed information about associated objects

### Inspection Example

When inspecting a layer:
- **Settings Column** - Shows layer properties, color, line type, etc.
- **Objects Column** - Lists all objects assigned to that layer
- **Usage Information** - Shows how many objects use the layer
- **Property Details** - Displays detailed property information

## Object Association Analysis

### Associated Objects Detection

The tool automatically detects and displays associated objects:

- **Direct Associations** - Objects directly assigned to the selected item
- **Indirect Associations** - Objects that reference the selected item
- **Nested Dependencies** - Objects that depend on the selected item through other objects
- **Usage Patterns** - Patterns of how the object is used

### Association Examples

Different types of associations:

#### Layer Associations
- **Objects on Layer** - All objects assigned to a specific layer
- **Layer Properties** - Layer color, line type, visibility settings
- **Usage Count** - Number of objects using the layer
- **Object Types** - Types of objects on the layer

#### Line Type Associations
- **Objects with Line Type** - All objects using a specific line type
- **Line Type Properties** - Line type definition and properties
- **Usage Distribution** - How the line type is used across objects
- **Style References** - Styles that reference the line type

## Detailed Inspection Process

### Step-by-Step Inspection

Complete inspection workflow:

1. **Select Object Type** - Choose the type of object to inspect
2. **Search for Objects** - Use search to find specific objects
3. **Select Object** - Choose the object to inspect
4. **View Results** - Examine associated settings and objects
5. **Analyze Dependencies** - Understand object relationships
6. **Make Decisions** - Decide on modification or deletion

### Inspection Results Analysis

Understanding inspection results:

- **Usage Assessment** - Determine if object is used or unused
- **Dependency Analysis** - Identify dependencies and relationships
- **Risk Assessment** - Evaluate risks of modification or deletion
- **Action Planning** - Plan appropriate actions based on results

## Advanced Inspection Features

### Multi-Object Inspection

Inspect multiple objects simultaneously:

- **Multi-selection** - Select multiple objects for inspection
- **Batch Analysis** - Analyze multiple objects at once
- **Comparative Analysis** - Compare inspection results between objects
- **Efficient Processing** - Process multiple objects efficiently

### Real-time Updates

See inspection results immediately:

- **Live Updates** - View results as they are processed
- **Dynamic Display** - Interface updates based on selections
- **Instant Feedback** - Immediate feedback on object selection
- **Real-time Filtering** - Filter results dynamically

## Best Practices

### Effective Inspection
- **Start with Search** - Use search to find specific objects quickly
- **Review Both Columns** - Examine both settings and objects columns
- **Check Dependencies** - Verify dependencies before making changes
- **Document Findings** - Keep records of inspection results

### Search and Filter Usage
- **Use Specific Terms** - Use specific search terms for better results
- **Combine Filters** - Use multiple filters for precise results
- **Save Useful Searches** - Remember useful search combinations
- **Regular Updates** - Update search results as needed

### Result Analysis
- **Understand Relationships** - Understand object relationships
- **Assess Usage** - Determine if objects are actively used
- **Plan Actions** - Plan appropriate actions based on results
- **Verify Decisions** - Verify decisions before taking action 
