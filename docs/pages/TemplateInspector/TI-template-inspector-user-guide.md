---
layout: default
title: Template Inspector User Guide
nav_order: 7
has_children: true
permalink: /docs/template-inspector-user-guide
---

# Template Inspector User Guide

Learn how to use Template Inspector to inspect object usage, find dependencies, and perform batch modifications to clean your files efficiently.
{: .fs-6 .fw-300 }

## Description

Template Inspector helps you inspect where objects are used so you can find their associated objects and delete them or modify their assignments to clean your files. The tool supports layers, line types, hatch styles, dimension styles, and text styles, performing depth scans to find usage and enabling batch modifications.

**Key Features:**
- **Multiple Object Types** - Inspect layers, line types, dimension styles, hatch styles, text styles
- **Search and Filter** - Find specific objects using search functionality
- **Object Inspection** - View associated settings and objects for each item
- **Object Selection and Isolation** - Select and isolate associated objects
- **Layer Swapping** - Change layer assignments for objects
- **Batch Updates** - Update multiple objects simultaneously
- **Object Deletion** - Delete unused objects with confirmation
- **Real-time Filtering** - Filter data by name or criteria

## Getting Started

### Main Interface

The Template Inspector tool is accessed directly from the plugin button. The main interface allows you to:

- **Select Object Types** - Choose from layers, line types, dimension styles, hatch styles, text styles
- **Search Objects** - Find specific objects using search functionality
- **Inspect Objects** - View detailed information about selected objects
- **Manage Objects** - Select, isolate, modify, and delete objects

### Basic Workflow

1. **Open Template Inspector** from the plugin button
2. **Select Object Type** - Choose the type of object to inspect
3. **Search/Filter** - Use search to find specific objects
4. **Inspect Objects** - View associated settings and objects
5. **Manage Objects** - Select, isolate, modify, or delete objects

## Object Types

### Supported Object Types

Template Inspector supports inspection of multiple object types:

- **Layers** - Inspect layer usage and associated objects
- **Line Types** - Find line type assignments and usage
- **Dimension Styles** - Check dimension style usage
- **Hatch Styles** - Locate hatch pattern usage
- **Text Styles** - Find text style assignments

### Object Selection

Choose which object type to inspect:

1. **Select Object Type** - Choose from the available object types
2. **View Object List** - See all objects of the selected type
3. **Search Objects** - Use search to find specific objects
4. **Filter Results** - Apply filters to narrow down results

## Search and Filter

### Search Functionality

Find specific objects quickly:

- **Search by Name** - Search for objects by name or partial name
- **Real-time Results** - See results as you type
- **Case-insensitive** - Search works regardless of case
- **Partial Matching** - Find objects with partial name matches

### Filtering Capabilities

Filter data to focus on specific items:

- **Name-based Filtering** - Filter by object names
- **Category Filtering** - Filter by object categories
- **Usage Filtering** - Filter by usage status
- **Dynamic Filtering** - Apply multiple filter criteria

## Object Inspection

### Detailed Object Information

View comprehensive information about selected objects:

- **Associated Settings** - See all settings related to the object
- **Associated Objects** - View objects that use the selected item
- **Usage Information** - Check how many objects are associated
- **Property Details** - View detailed property information

### Inspection Results

The tool displays detailed inspection results:

- **Settings Column** - Shows all associated settings for the object
- **Objects Column** - Lists all objects associated with the item
- **Usage Count** - Shows number of associated objects
- **Property Values** - Displays current property values

## Object Management

### Object Selection

Select and manage associated objects:

- **Select Objects** - Choose specific objects from the list
- **Multi-selection** - Select multiple objects simultaneously
- **Select All** - Select all objects in the current view
- **Clear Selection** - Clear current selection

### Object Isolation

Isolate objects for focused inspection:

- **Isolate Objects** - Show only selected objects
- **End Isolation** - Return to full view
- **Focused Inspection** - Inspect isolated objects in detail
- **Visual Confirmation** - See isolated objects clearly

## Layer Management

### Layer Swapping

Change layer assignments for objects:

- **Select Target Layer** - Choose the new layer for assignment
- **Update Objects** - Apply layer changes to selected objects
- **Confirmation** - Confirm changes before applying
- **Verification** - Check that changes were applied correctly

### Layer Assignment Process

Complete layer swapping workflow:

1. **Select Objects** - Choose objects to modify
2. **Choose New Layer** - Select target layer for assignment
3. **Update Objects** - Apply layer changes
4. **Confirm Changes** - Verify changes were applied
5. **Check Results** - Verify objects now use new layer

## Batch Operations

### Batch Updates

Update multiple objects simultaneously:

- **Multi-selection** - Select multiple objects for batch operations
- **Batch Updates** - Apply changes to all selected objects
- **Confirmation** - Confirm batch operations before applying
- **Progress Tracking** - Monitor batch operation progress

### Batch Modification Workflow

1. **Select Objects** - Choose multiple objects to modify
2. **Choose Action** - Select the modification to apply
3. **Configure Settings** - Set up modification parameters
4. **Apply Changes** - Execute batch modification
5. **Verify Results** - Check that all changes were applied

## Object Deletion

### Safe Deletion

Delete unused objects safely:

- **Unused Object Detection** - Identify objects that are not used
- **Deletion Confirmation** - Confirm deletion before proceeding
- **Safety Checks** - Verify objects can be safely deleted
- **Backup Recommendations** - Suggest backups for important operations

### Deletion Process

Safe object deletion workflow:

1. **Identify Unused Objects** - Find objects that are not referenced
2. **Review Dependencies** - Check for any hidden dependencies
3. **Confirm Deletion** - Confirm deletion action
4. **Execute Deletion** - Remove unused objects
5. **Verify Cleanup** - Confirm objects were removed

## Advanced Features

### Component Configuration

Modify component settings directly:

- **Component Inspection** - Inspect component configurations
- **Direct Modification** - Change component settings from the UI
- **Setting Updates** - Update component properties
- **Configuration Management** - Manage component configurations

### Real-time Updates

See changes immediately:

- **Live Updates** - View changes as they happen
- **Real-time Filtering** - Filter data dynamically
- **Instant Results** - See search and filter results immediately
- **Dynamic Interface** - Interface updates based on selections

## Best Practices

### Object Inspection
- **Start with Search** - Use search to find specific objects quickly
- **Inspect Before Modifying** - Always inspect objects before making changes
- **Check Dependencies** - Verify dependencies before deletion
- **Use Isolation** - Use isolation for focused inspection

### Batch Operations
- **Test on Small Sets** - Test batch operations on small object sets first
- **Verify Changes** - Always verify that changes were applied correctly
- **Backup Important Data** - Backup important data before major operations
- **Document Changes** - Keep records of modifications made

### Safety Measures
- **Confirm Actions** - Always confirm destructive actions
- **Review Dependencies** - Check object dependencies before deletion
- **Test Modifications** - Test modifications before applying to production
- **Monitor Results** - Monitor results after applying changes


