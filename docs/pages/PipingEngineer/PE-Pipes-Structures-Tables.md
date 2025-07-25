---
layout: default
title: Pipes and Structures Tables
parent: Piping Engineer User Guide
nav_order: 2
---

# Pipes and Structures Tables
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Pipes and Structures Tables

The Pipes and Structures Tables feature allows you to edit pipes or structures data efficiently. You can add and customize multiple properties to the tables for comprehensive piping network management.

## Overview

Piping Engineer provides dedicated tables for managing both pipes and structures within your piping networks. These tables offer:

- **Bulk editing capabilities** for multiple pipes and structures
- **Customizable property columns** to match your project requirements
- **Real-time validation** of piping network integrity
- **Mass property updates** across entire networks

## Selecting Pipes and Structures

### Pipes Table

Steps:
1. Select the "Pipes" tab in the Piping Engineer interface
2. Choose your selection method:
   - **Whole Network**: Select all pipes in the current piping system
   - **Active View**: Select pipes visible in the current view
   - **Current Selection**: Select only the pipes you've pre-selected in Revit

![Piping Engineer selecting pipes](../../../assets\images\PipingEngineer\PE-SelectPipes.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Structures Table

Steps:
1. Select the "Structures" tab in the Piping Engineer interface
2. Choose your selection method:
   - **Whole Network**: Select all structures in the current piping system
   - **Active View**: Select structures visible in the current view
   - **Current Selection**: Select only the structures you've pre-selected in Revit

![Piping Engineer selecting structures](../../../assets\images\PipingEngineer\PE-SelectStructures.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

## Customizing Table Properties

### Adding Properties

You can customize the tables by adding specific properties that are relevant to your piping design workflow.

Steps:
1. Click on the "Add Property" button in the table toolbar
2. Select from available properties:
   - **Instance Parameters**: Properties specific to individual pipes/structures
   - **Type Parameters**: Properties shared by similar pipe/structure types
   - **System Parameters**: Built-in Revit system properties
   - **Custom Parameters**: User-defined project parameters

![Piping Engineer adding properties](../../../assets\images\PipingEngineer\PE-AddProperties.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Property Categories

The available properties are organized into categories for easy selection:

```yaml
# Common Pipe Properties:
- Diameter/Size
- Material
- System Type
- Elevation
- Slope
- Flow Direction
- Insulation
- Fitting Type

# Common Structure Properties:
- Structure Type
- Elevation
- Invert Level
- Cover Depth
- Material
- Size/Dimensions
- Connection Type
```

### Reordering Properties

Use the arrows in the table header to reorder properties according to your workflow preferences.

![Piping Engineer reordering properties](../../../assets\images\PipingEngineer\PE-ReorderProperties.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

## Editing Data

### Bulk Editing

Piping Engineer supports bulk editing operations for efficient network management:

1. **Select multiple rows** in the table using Ctrl+Click or Shift+Click
2. **Edit a cell** in the selected range
3. **Apply to all selected** items simultaneously

![Piping Engineer bulk editing](../../../assets\images\PipingEngineer\PE-BulkEdit.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Validation

The tool provides real-time validation to ensure network integrity:

- **Slope validation** against design standards
- **Elevation consistency** checks
- **Connection compatibility** verification
- **System type** validation

![Piping Engineer validation](../../../assets\images\PipingEngineer\PE-Validation.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

## Export and Import

### Exporting Data

You can export the table data to Excel for external analysis or collaboration:

1. Click the "Export" button in the table toolbar
2. Choose your export format (Excel, CSV)
3. Select the destination folder
4. The exported file will include all visible properties and their current values

![Piping Engineer exporting data](../../../assets\images\PipingEngineer\PE-ExportData.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Importing Data

After external editing, you can import the data back to update your Revit model:

1. Click the "Import" button in the table toolbar
2. Select your edited file
3. Review the changes in the preview window
4. Apply the updates to your Revit model

![Piping Engineer importing data](../../../assets\images\PipingEngineer\PE-ImportData.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

## Search and Filter

### Searching Properties

Use the search box to quickly find specific properties in the table:

![Piping Engineer searching properties](../../../assets\images\PipingEngineer\PE-SearchProperties.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub>

### Filtering Data

Apply filters to focus on specific subsets of your piping network:

- **System Type**: Filter by piping system (sanitary, storm, etc.)
- **Material**: Filter by pipe/structure material
- **Size Range**: Filter by diameter or dimensions
- **Elevation Range**: Filter by elevation values

![Piping Engineer filtering data](../../../assets\images\PipingEngineer\PE-FilterData.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiRootsOne](https://diroots.com/revit-plugins/dirootsone/).</sub> 