---
layout: default
title: Editing Features
parent: Style Helper User Guide
nav_order: 3
---

# Editing Features
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Editing Features

Style Helper provides comprehensive editing capabilities for customizing table data, editing style data properties, and performing batch operations for efficient data edition.

## Overview

The editing features include:
- **Table Column Preferences** - Configure table structure and data display
- **Data Editing** - Edit style properties for all three tabs
- **Batch Editing** - Edit multiple objects and rows simultaneously
- **Children Styles Support** - Edit children nested label styles


## Table Customization

### Customizing Table Data Structure

Style Helper allows you to customize the table structure to show only the data you need:

#### Preferences Button
- **Independent Control** - Each tab has its own Preferences button for column configuration
- **Dynamic Configuration** - Available column options change based on checked objects
- **Tab-Specific Settings** - Column settings are configured independently for each tab

#### Column Preferences
After accessing the preferences, you can:
- **Add Columns**
- **Remove Columns** - Remove unnecessary columns
- **Reorder Columns** - Arrange columns in preferred order


> **GIF Placeholder:** Show table customization and profile management

## Data Editing for the Different Tabs

### Styles Tab Editing

Edit Civil 3D object style property data directly in the table:

#### Editing Property Data Process

1. **Access the Tab** - Open the Styles tab you want to edit
2. **Check Objects** - Check specific objects to work with
3. **Configure Columns** - Use Preferences button to configure table columns
4. **Edit Properties** - Modify style properties directly in the table
5. **Save Changes** - Changes are applied

> **GIF Placeholder:** Show Object Styles tab editing process
> **GIF Placeholder:** Show Styles tab editing process
> **GIF Placeholder:** Show Table Styles tab editing process

## Batch Editing

### Multiple Row Data Editing

Edit multiple objects, style or table rows simultaneously for efficient workflow:

#### Selection Process
- **Multi-selection** - Select multiple rows in the table
- **Bulk Modifications** - Apply changes to one column object and the change will be propagated to the set of selected rows at once
- **Validate Changes** - Ensure consistent changes across all selected items
- **Efficiency** - Save time with bulk operations

- **Visual Validation** - See which objects or rows are affected by changes based on the status column

- **Apply Changes** - Apply changes to the modified items

> **GIF Placeholder:** Show multiple row data editing process for both objects and table rows

### Main Component–Subcomponent Relationships in Batch Editing

Since the tool displays all subcomponents, some data may be associated with the main component. Editing a property of the main component can affect multiple rows, because the main component controls several subcomponents.

#### Understanding Main Component–Subcomponent Data
- **Main Component Properties** – Some data belongs to the main component
- **Subcomponents** – Subcomponents have their own specific data
- **Multiple Row Impact** – Editing main component properties can impact multiple rows

#### Main Component Property Editing
- **Main Component Changes** – Changes to main component properties affect all related subcomponents
- **Cascading Updates** – Updates to the main component automatically update its subcomponents
- **Bulk Modifications** – Modify main component properties to update several subcomponents at once

> **Note:** To identify which rows represent subcomponents or main components during batch editing, refer to the **Component** column in the table. The structure and naming in the Component column are explained in the following reference: [Component Column Reference](SH-Object-Label-Table-Styles.md#component-column-reference)

> **GIF Placeholder:** Show main component–subcomponent relationship editing and its impact on multiple rows

## Missing Object Limitations

Due to current Civil 3D API limitations, Style Helper cannot collect the following style types:

- **Section View Styles** - Drafting buffer outline
- **Rail Turnout** - All rail turnout related styles
- **Can't View Styles** - Equilibrium can't line annotation, Applied cant line annotation
- **Bridge Styles** - All bridge related styles

These limitations are imposed by the Civil 3D API and are not within the control of Style Helper. We continue to monitor API updates and will add support for these styles when they become available through the Civil 3D API.


## Label Styles Children Component Editing

Style Helper supports children label styles editing capabilities.

Civil 3D has hierarchical component structures for label styles:

- **Parent label Styles** - Main style objects (e.g., Point Label Styles)
- **Child Label Style** - Inside the parent label style it could have additional nested children and subchildren label styles. We are also supporting these

Style Helper supports children label styles editing capabilities.

> **GIF Placeholder:** Display support for the parent-child label style relationship structure