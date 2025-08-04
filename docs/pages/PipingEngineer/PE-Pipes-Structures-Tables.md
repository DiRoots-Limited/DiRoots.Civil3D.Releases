---
layout: default
title: Pipes and Structures Tables
parent: Piping Engineer User Guide
nav_order: 1
---

# Pipes and Structures Tables
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Pipes and Structures Tables

The Pipes and Structures Tables feature allows you to edit pipes or structures data efficiently. You can add and customize multiple properties to the tables for comprehensive data management.

## Overview

Piping Engineer provides two separate tables for managing data for both Pipes and Structures within your piping networks. The interface displays:

- **Pipe table (left)**: For managing pipe data and properties
- **Structure table (right)**: For managing structure data and properties

These tables offer:

- **Bulk editing capabilities** for single or multiple pipes or structures
- **Customizable property columns** to match your project requirements or specific use case
- **Rule validation context** Tables highlights the objects violating the Civil3D rules
- **Mass property updates** across entire networks

## Table Layout

The interface displays two separate tables:

- **Pipe table (left)**: Shows pipe data and properties based on the selected mode
- **Structure table (right)**: Shows structure data and properties based on the selected mode

A draggable separator is provided between the Pipe table (left) and the Structure table (right), allowing you to resize each table according to your preference. 


Insert Gif placeholder

## Selecting Pipes and Structures

### Selection Modes

The selection modes affect the list of elements displaied for both the Pipe table (left) and Structure table (right) simultaneously. Choose your selection method between:

- **By Selected Pipes & Structures**: The tables display only the pipes and structures you've pre-selected in Civil 3D

Insert Gif placeholder

- **By Piping Network**: Select all pipes and structures in a specific piping network (use the dropdown to choose the network)

Insert Gif placeholder

- **By Pipe Run**: Select pipes and structures between two specified elements (enter the initial and last pipe/structure)

Insert Gif placeholder



## Customizing Table Properties

### Adding Properties

You can customize the tables by adding specific properties that are relevant to your piping design workflow or use case.

Steps:
 Click on the "Preferences" button in the table toolbar and add the properties required as needed . 
2. Select from available properties:
   - **Instance Parameters**: Properties specific to individual pipes/structures
   - **Type Parameters**: Properties shared by similar pipe/structure types
   - **System Parameters**: Built-in Civil 3D system properties
   - **Custom Parameters**: User-defined project parameters

![Piping Engineer adding properties](../../../assets\images\PipingEngineer\PE-AddProperties.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

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
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

## Editing Data

### Bulk Editing

Piping Engineer supports bulk editing operations for efficient network management:

1. **Select multiple rows** in the table using Ctrl+Click or Shift+Click
2. **Edit a cell** in the selected range
3. **Apply to all selected** items simultaneously

![Piping Engineer bulk editing](../../../assets\images\PipingEngineer\PE-BulkEdit.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>



## Search and Filter

### Searching Properties

Use the search box to quickly find specific properties in the table:

![Piping Engineer searching properties](../../../assets\images\PipingEngineer\PE-SearchProperties.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub>

### Filtering Data

Apply filters to focus on specific subsets of your piping network:

- **System Type**: Filter by piping system (sanitary, storm, etc.)
- **Material**: Filter by pipe/structure material
- **Size Range**: Filter by diameter or dimensions
- **Elevation Range**: Filter by elevation values

![Piping Engineer filtering data](../../../assets\images\PipingEngineer\PE-FilterData.gif)  
<sub>Note: the version on the image may not reflect the [latest version of Piping Engineer/DiCivil](https://diroots.com/Civil 3D-plugins/DiCivil/).</sub> 
