---
layout: default
title: Usage Display
parent: Template Inspector User Guide
nav_order: 3
---

# Usage Display
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Usage Display

Template Inspector clearly displays object usage information, showing associated settings and objects for each inspected item. The tool provides comprehensive usage analysis to help you make informed decisions about object management and cleanup.

## Overview

Usage display is a key feature that shows you exactly how objects are used in your files. The tool displays associated settings and objects in a clear, organized format, enabling you to understand dependencies and make informed decisions about modification or deletion.

## Two-Column Display Format

### Settings Column

The left column displays all settings associated with the selected object:

- **Associated Settings** - All settings related to the selected object
- **Property Values** - Current property values and configurations
- **Setting Details** - Detailed information about each setting
- **Configuration Data** - Complete configuration information

### Objects Column

The right column displays all objects associated with the selected item:

- **Associated Objects** - All objects that use the selected item
- **Usage Count** - Number of objects associated with the item
- **Object Types** - Types of objects using the selected item
- **Object Details** - Detailed information about associated objects

## Usage Status Indicators

### Usage Assessment

The tool provides clear indicators of object usage:

- **Used Objects** - Objects that are actively used in the file
- **Unused Objects** - Objects that are not referenced anywhere
- **Partially Used** - Objects with some usage but may be safe to delete
- **Usage Count** - Shows how many times each object is referenced

### Usage Examples

Different usage scenarios:

#### Active Usage
- **Objects with Associations** - Objects that have associated items
- **Usage Count > 0** - Objects that are referenced by other items
- **Active Dependencies** - Objects with active dependencies
- **Safe to Keep** - Objects that should not be deleted

#### No Usage
- **No Associated Objects** - Objects with no associated items
- **Usage Count = 0** - Objects that are not referenced
- **No Dependencies** - Objects with no dependencies
- **Safe to Delete** - Objects that can be safely removed

## Associated Objects Display

### Object Association Detection

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

## Filtering and Search

### Real-time Filtering

Filter the display to focus on specific items:

- **Name-based Filtering** - Filter by object names
- **Category Filtering** - Filter by object categories
- **Usage Filtering** - Filter by usage status
- **Dynamic Filtering** - Apply multiple filter criteria simultaneously

### Search Functionality

Find specific items quickly:

- **Search by Name** - Search for objects by name or partial name
- **Real-time Results** - See results as you type
- **Case-insensitive** - Search works regardless of case
- **Partial Matching** - Find objects with partial name matches

### Filter Example

Using the filter functionality:
- **Filter "Surface"** - Show only objects with "Surface" in the name
- **Narrow Results** - Focus on specific categories or types
- **Quick Location** - Quickly locate objects in large datasets
- **Efficient Navigation** - Navigate through filtered results

## Usage Analysis

### Making Informed Decisions

Use usage information to make decisions:

- **Usage Assessment** - Determine if object is actively used
- **Dependency Analysis** - Identify dependencies and relationships
- **Risk Assessment** - Evaluate risks of modification or deletion
- **Action Planning** - Plan appropriate actions based on usage

### Decision Guidelines

Guidelines for different usage scenarios:

#### Used Objects
- **Keep Objects** - Objects with active usage should be kept
- **Review Dependencies** - Check dependencies before modification
- **Plan Carefully** - Plan modifications carefully to avoid breaking dependencies
- **Document Changes** - Document any changes made to used objects

#### Unused Objects
- **Safe to Delete** - Objects with no usage can be safely deleted
- **Clean Up** - Remove unused objects to clean up files
- **Verify Unused Status** - Double-check that objects are truly unused
- **Backup Before Deletion** - Backup important data before deletion

## Advanced Display Features

### Multi-Object Display

Display information for multiple objects:

- **Multi-selection** - Select multiple objects for display
- **Comparative Analysis** - Compare usage between objects
- **Batch Assessment** - Assess usage for multiple objects at once
- **Efficient Review** - Review multiple objects efficiently

### Real-time Updates

See updates immediately:

- **Live Updates** - View updates as they happen
- **Dynamic Display** - Display updates based on selections
- **Instant Feedback** - Immediate feedback on object selection
- **Real-time Filtering** - Filter results dynamically

## Best Practices

### Effective Usage Analysis
- **Review Both Columns** - Examine both settings and objects columns
- **Check Usage Count** - Pay attention to usage count information
- **Understand Dependencies** - Understand object dependencies
- **Plan Actions** - Plan actions based on usage analysis

### Filter and Search Usage
- **Use Specific Filters** - Use specific filters for better results
- **Combine Search and Filter** - Use search and filter together
- **Save Useful Filters** - Remember useful filter combinations
- **Regular Updates** - Update filters as needed

### Decision Making
- **Assess Usage** - Determine if objects are actively used
- **Check Dependencies** - Verify dependencies before actions
- **Plan Modifications** - Plan modifications carefully
- **Document Decisions** - Document decisions and actions 
