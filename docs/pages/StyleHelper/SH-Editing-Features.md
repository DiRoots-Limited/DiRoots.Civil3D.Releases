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

Style Helper provides comprehensive editing capabilities for customizing table data, editing style properties across all three tabs, and performing batch operations for efficient workflow management.

## Overview

The editing features include:
- **Table Customization** - Configure table structure and data display
- **Data Editing** - Edit style properties for all three tabs
- **Batch Editing** - Edit multiple objects and rows simultaneously
- **Children Styles Support** - Edit children nested label styles

> **GIF Placeholder:** Show overview of editing features

## Table Customization

### Customizing Table Data Structure

Style Helper allows you to customize the table structure to show the data you need:

#### Preferences Button
- **Independent Control** - Each tab has its own Preferences button for column configuration
- **Dynamic Configuration** - Available column options change based on checked objects
- **Tab-Specific Settings** - Column settings are configured independently for each tab
- **Persistent Configuration** - Your preferences for each tab are saved across sessions

#### Column Management
- **Add Columns** - Add columns from object preferences
- **Remove Columns** - Remove unnecessary columns
- **Reorder Columns** - Arrange columns in preferred order
- **Column Visibility** - Show/hide columns as needed

#### Profile System
- **Save Profiles** - Save column configurations for reuse
- **Load Profiles** - Load saved column configurations
- **Profile Switching** - Switch between different configurations quickly
- **Tab-Specific Profiles** - Each tab maintains its own profile settings

> **GIF Placeholder:** Show table customization and profile management

## Data Editing for Three Tabs

### Object Styles Tab Editing

Edit Civil 3D object style properties directly in the table:

#### Editable Properties
- **Display Properties** - Edit display-related style properties
- **Geometry Properties** - Modify geometry-related style settings
- **Analysis Properties** - Configure analysis-related style properties
- **Behavior Properties** - Adjust style behavior settings

#### Editing Process
1. **Select Object Type** - Choose the object type (e.g., Surface)
2. **Check Objects** - Select specific objects to work with
3. **Configure Columns** - Use Preferences button to configure table columns
4. **Edit Properties** - Modify style properties directly in the table
5. **Save Changes** - Changes are applied automatically

> **GIF Placeholder:** Show Object Styles tab editing process

### Label Styles Tab Editing

Edit Civil 3D label style properties and components:

#### Editable Properties
- **Text Components** - Edit text content and formatting
- **Line Components** - Modify line and leader components
- **Block Components** - Configure block and symbol components
- **Border Components** - Edit border and background components

#### Editing Process
1. **Select Label Type** - Choose the label type (e.g., Point)
2. **Check Label Styles** - Select specific label styles to work with
3. **Configure Columns** - Use Preferences button to configure table columns
4. **Edit Properties** - Modify label properties directly in the table
5. **Save Changes** - Changes are applied automatically

> **GIF Placeholder:** Show Label Styles tab editing process

### Table Styles Tab Editing

Edit Civil 3D table style properties and components:

#### Editable Properties
- **Table Layout** - Edit table layout and structure
- **Column Properties** - Modify column formatting and behavior
- **Header Properties** - Configure table header settings
- **Data Properties** - Edit data formatting and display

#### Editing Process
1. **Select Table Type** - Choose the table type (e.g., Surface Table)
2. **Check Table Styles** - Select specific table styles to work with
3. **Configure Columns** - Use Preferences button to configure table columns
4. **Edit Properties** - Modify table properties directly in the table
5. **Save Changes** - Changes are applied automatically

> **GIF Placeholder:** Show Table Styles tab editing process

## Batch Editing

### Multi-Object Editing

Edit multiple objects simultaneously for efficient workflow:

#### Object Selection
- **Multi-selection** - Check multiple objects in the tree structure
- **Bulk Modifications** - Apply changes to multiple objects at once
- **Consistent Updates** - Ensure consistent changes across objects
- **Efficiency** - Save time with bulk operations

#### Object-Level Changes
When you select multiple objects, changes are applied to all selected objects:
- **Property Updates** - Update properties across all selected objects
- **Style Modifications** - Modify styles for multiple objects simultaneously
- **Data Consistency** - Maintain data consistency across objects
- **Visual Feedback** - See which objects are affected by changes

> **GIF Placeholder:** Show multi-object editing process

### Multi-Row Editing

Edit multiple table rows simultaneously:

#### Row Selection
- **Select Multiple Rows** - Select multiple rows in the table
- **Bulk Property Editing** - Edit properties across selected rows
- **Consistent Changes** - Apply consistent changes to multiple rows

#### Row-Level Operations
After selecting multiple rows:
- **Property Editing** - Edit the required property
- **Data Updates** - The tool updates data values across multiple selected rows
- **Apply Changes** - Apply style changes to multiple rows

> **GIF Placeholder:** Show multi-row editing process

### Parent-Child Relationships in Batch Editing

#### Understanding Parent-Child Data
- **Parent Properties** - Some data belongs to the main parent component
- **Child Components** - Subcomponents have their own specific data
- **Multiple Row Impact** - Editing parent properties affects multiple rows
- **Visual Indicators** - Checkboxes show which rows are affected by parent changes

#### Parent Property Editing
- **Parent-Level Changes** - Changes to parent properties affect all child components
- **Cascading Updates** - Parent changes automatically update child components
- **Bulk Modifications** - Modify parent properties to update multiple components
- **Visual Feedback** - Clear indication of parent-child relationships

#### Important Note
Since the tool shows all subcomponents, some data could be related to the main component. This means editing one property might affect more than one row because it's editing the main parent component that controls multiple subcomponents.

> **GIF Placeholder:** Show parent-child relationship editing and its impact on multiple rows

## Children Styles Support

### Children Nested Label Style Editing

Style Helper supports editing children nested label styles with granular control:

#### Understanding Children Styles
- **Parent-Child Structure** - Label styles can have nested children components
- **Component Hierarchy** - Each component can have its own properties
- **Inheritance** - Children can inherit properties from parent components
- **Override Capabilities** - Children can override inherited properties

#### Children Style Editing Process
1. **Access Children Data** - Use Object Preferences to load children component data
2. **Identify Components** - Identify which components are children vs parent
3. **Edit Individual Components** - Edit specific children components
4. **Manage Inheritance** - Control how properties are inherited or overridden
5. **Apply Changes** - Changes are applied to the specific children components

#### Children Component Properties
- **Component-Specific Data** - Each child component has its own properties
- **Inherited Properties** - Properties inherited from parent components
- **Override Properties** - Properties that override parent settings
- **Independent Editing** - Edit children components independently

> **GIF Placeholder:** Show children styles editing and component management

## Missing Object Limitations

Due to current Civil 3D API limitations, Style Helper cannot collect the following style types:

- **Section View Styles** - Drafting buffer outline
- **Rail Turnout** - All rail turnout related styles
- **Can't View Styles** - Equilibrium can't line annotation, Applied cant line annotation
- **Bridge Styles** - All bridge related styles

These limitations are imposed by the Civil 3D API and are not within the control of Style Helper. We continue to monitor API updates and will add support for these styles when they become available through the Civil 3D API.


## Children Component Editing

Style Helper supports children label styles with comprehensive editing capabilities.

### Understanding Parent-Child Relationships

Civil 3D Label Styles have hierarchical component structures for label styles:

- **Parent label Styles** - Main style objects (e.g., Point Label Styles)
- **Child Label Style** - Inside the parent label style it could have additional nested children and subchildren label styles. We are also supporting these

> **GIF Placeholder:** Display support for the parent-child label style relationship structure

## Best Practices

- **Use Profiles** - Save and reuse column configurations for efficiency
- **Batch Operations** - Use multi-selection for consistent changes across multiple objects
- **Understand Relationships** - Be aware of parent-child relationships when editing
- **Test Changes** - Verify changes are applied correctly after editing
- **Backup Configurations** - Save important column configurations as profiles
