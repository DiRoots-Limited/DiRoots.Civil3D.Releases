---
layout: default
title: Transfer Point Description Keys
parent: Transfer Survey Standards User Guide
nav_order: 1
---

# Transfer Point Description Keys
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Transfer Point Description Keys

Transfer Survey Standards enables you to transfer Point Description Keys (PDKs) between Civil 3D projects, whether the source files are open or closed, while preserving all key configurations and associated data. The tool provides comprehensive conflict resolution and layer validation capabilities.

## Overview

Point Description Keys are essential components of Civil 3D survey standards that define how points are labeled and displayed. The Transfer Survey Standards tool allows you to efficiently transfer these configurations between projects, ensuring consistency across your survey workflows.

## Transfer Capabilities

### Multiple Source Options

Transfer Point Description Keys from various sources:

- **Open Files** - Transfer PDKs from currently open Civil 3D drawings
- **Closed Files** - Transfer PDKs from closed Civil 3D files without opening them
- **Excel Spreadsheets** - Import PDKs from Excel files for external editing
- **Multiple Sources** - Transfer from multiple source files simultaneously

### Transfer Process

1. **Select Source** - Choose the source Civil 3D file (open or closed)
2. **Import Data** - Load Point Description Keys from the source
3. **Review Data** - Examine imported PDKs for accuracy
4. **Edit if Needed** - Modify values before applying
5. **Handle Conflicts** - Resolve conflicts between existing and imported data
6. **Apply Changes** - Transfer PDKs to target files

![Transfer Survey Standards transfer point description keys](../../../assets/images/TransferSurveyStandards/TSS-TransferPointDescriptionKeys.gif)
<sub>Note: the version on the image may not reflect the latest version of Transfer Survey Standards.</sub>

## Conflict Resolution

### Conflict Detection

The tool automatically detects conflicts between existing and imported data:

- **Existing Data** - Identifies PDKs that already exist in target files
- **Data Differences** - Highlights differences between existing and imported data
- **User Choice** - Prompts user to choose replacement or retention
- **Selective Resolution** - Handle conflicts on a case-by-case basis

### Conflict Resolution Process

1. **Conflict Identification** - Tool identifies conflicts between existing and imported PDKs
2. **User Prompt** - System asks if you want to replace existing data with imported data
3. **Choice Options**:
   - **Replace** - Replace existing PDK with imported data
   - **Retain** - Keep existing PDK and skip imported data
4. **Confirmation** - Confirm your choice to proceed
5. **Update** - System updates the data based on your selection

### Example Conflict Scenario

When importing PDKs, you might encounter:
- **Existing Point Label Style** - Target file already has a point label style
- **Different Data** - Imported data has different properties than existing data
- **User Decision** - Choose to replace existing style or retain current style
- **Data Update** - System updates based on your choice

## Layer Validation

### Missing Layer Detection

The tool includes a warning system for missing layer definitions:

- **Layer Validation** - Checks if required layers exist in target files
- **Warning Messages** - Displays warnings for missing layers
- **User Awareness** - Ensures users are aware of missing layer definitions
- **Future Enhancement** - Warning system will be improved in next version

### Layer Management

Handle missing layer scenarios:

- **Layer Creation** - Create missing layers before transfer
- **Data Modification** - Modify imported data to use existing layers
- **Validation** - Verify all required layers are available
- **Error Prevention** - Prevent transfer errors due to missing layers

## Data Editing Before Import

### Pre-import Modifications

Edit PDK data before applying to target files:

- **Column Management** - Add or modify columns as needed
- **Value Editing** - Change values before importing
- **Data Validation** - Ensure data integrity before transfer
- **Bulk Modifications** - Make changes to multiple PDKs simultaneously

### Editing Workflow

1. **Import Data** - Load PDKs from source
2. **Review Structure** - Examine data structure and columns
3. **Add Columns** - Add missing columns (e.g., layer columns)
4. **Edit Values** - Modify values as needed
5. **Validate Data** - Check data integrity
6. **Apply Changes** - Import modified data

### Example Editing Scenario

When importing from Excel:
- **Missing Layer Column** - Excel file doesn't have layer assignments
- **Add Layer Column** - Add layer column to the data
- **Assign Layers** - Assign appropriate layers to PDKs
- **Import Data** - Import modified data with layer assignments

## Point Description Key Components

### Key Properties

Point Description Keys contain various properties:

- **Key Names** - Point description key identifiers and naming conventions
- **Format Codes** - Format specifications for point descriptions
- **Layer Assignments** - Layer assignments for different point types
- **Point Styles** - Point style configurations and display properties
- **Additional Properties** - Other associated properties and settings

### Transfer Options

Flexible transfer capabilities:

- **Complete Transfer** - Transfer all Point Description Keys
- **Selective Transfer** - Choose specific keys or key categories
- **Property Mapping** - Map properties between different naming conventions
- **Conflict Resolution** - Handle conflicts between existing and transferred keys

## Advanced Features

### Search and Filter

Quickly locate specific PDKs:

- **Search Functionality** - Find specific PDKs in large datasets
- **Filter Options** - Filter PDKs by various criteria
- **Efficient Navigation** - Quickly locate and modify specific keys
- **Data Organization** - Organize PDKs for easier management

### Excel Integration

Export and import PDKs via Excel:

- **Export to Excel** - Export PDKs for external editing
- **Import from Excel** - Import modified PDKs back to the tool
- **Template Support** - Use structured Excel templates
- **Data Validation** - Validate Excel data before import

## Best Practices

### Transfer Preparation
- **Verify Source Data** - Ensure source files contain valid PDKs
- **Check Layer Definitions** - Verify required layers exist in target files
- **Backup Original Data** - Keep backups of original configurations
- **Test Transfers** - Test transfers with small datasets first

### Conflict Management
- **Review Conflicts** - Carefully examine conflict details
- **Choose Wisely** - Select appropriate conflict resolution action
- **Document Decisions** - Keep records of conflict resolution choices
- **Verify Results** - Confirm that conflict resolution worked correctly

### Data Validation
- **Check Data Integrity** - Verify PDK data is complete and valid
- **Validate Layer Assignments** - Ensure layer assignments are correct
- **Test Functionality** - Verify PDKs work correctly after transfer
- **Document Changes** - Keep records of transferred configurations 
