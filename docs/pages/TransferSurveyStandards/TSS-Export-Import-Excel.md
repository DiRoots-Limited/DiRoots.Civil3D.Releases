---
layout: default
title: Export and Import Excel
parent: Transfer Survey Standards User Guide
nav_order: 3
---

# Export and Import Excel
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Export and Import Excel

Transfer Survey Standards provides comprehensive Excel export and import functionality for Point Description Keys and Figure Prefix Database, enabling you to transfer survey standards data efficiently and maintain data integrity. The tool includes search, filter, and data editing capabilities.

## Overview

Excel integration allows you to export survey standards data for external editing and import modified data back to the tool. This workflow is similar to Transfer Object Layers, providing a familiar experience for users. The tool supports data editing before import and includes search and filter capabilities for efficient data management.

## Excel Export Features

### Comprehensive Data Export

Export survey standards data to Excel format:

- **Point Description Keys Export** - Export all PDK configurations
- **Figure Prefix DB Export** - Export complete Figure Prefix Database
- **Structured Templates** - Pre-formatted Excel templates for consistent data structure
- **Multiple Formats** - Support for various Excel formats (.xlsx, .xls, .csv)

### Export Process

Complete export workflow:

1. **Select Data Type** - Choose to export PDKs, Figure Prefix DB, or both
2. **Choose Template** - Select appropriate Excel template for your data
3. **Configure Export** - Set export options and data selection
4. **Generate File** - Create Excel file with structured survey standards data
5. **Review Output** - Verify exported data structure and content

![Transfer Survey Standards export to Excel](../../../assets/images/TransferSurveyStandards/TSS-ExportExcel.gif)
<sub>Note: the version on the image may not reflect the latest version of Transfer Survey Standards.</sub>

## Excel Import Features

### Data Import Capabilities

Import survey standards data from Excel:

- **Template Validation** - Validate imported data against template structure
- **Data Mapping** - Map Excel data to Civil 3D survey standards
- **Error Handling** - Identify and resolve import errors
- **Batch Import** - Import multiple Excel files simultaneously

### Import Process

Complete import workflow:

1. **Select Template** - Choose Excel template format for import
2. **Load File** - Select Excel file containing survey standards data
3. **Validate Data** - Review and validate imported data structure
4. **Edit Data** - Modify data before applying (if needed)
5. **Map Settings** - Map Excel data to target Civil 3D survey standards
6. **Apply Changes** - Import settings to target file

![Transfer Survey Standards import from Excel](../../../assets/images/TransferSurveyStandards/TSS-ImportExcel.gif)
<sub>Note: the version on the image may not reflect the latest version of Transfer Survey Standards.</sub>

## Data Editing Before Import

### Pre-import Modifications

Edit data before applying to target files:

- **Column Management** - Add or modify columns as needed
- **Value Editing** - Change values before importing
- **Data Validation** - Ensure data integrity before transfer
- **Bulk Modifications** - Make changes to multiple items simultaneously

### Editing Workflow

Complete editing process:

1. **Import Excel Data** - Load data from Excel file
2. **Review Structure** - Examine data structure and columns
3. **Add Missing Columns** - Add columns that don't exist (e.g., layer columns)
4. **Edit Values** - Modify values as needed
5. **Validate Data** - Check data integrity
6. **Apply Changes** - Import modified data

### Example Editing Scenario

When importing from Excel:
- **Missing Layer Column** - Excel file doesn't have layer assignments
- **Add Layer Column** - Add layer column to the data
- **Assign Layers** - Assign appropriate layers to PDKs
- **Import Data** - Import modified data with layer assignments

## Search and Filter Capabilities

### Search Functionality

Quickly locate specific data:

- **Search Rows** - Find specific items in large datasets
- **Filter Options** - Filter data by various criteria
- **Efficient Navigation** - Quickly locate and modify specific items
- **Data Organization** - Organize data for easier management

### Filter Features

Advanced filtering capabilities:

- **Column-based Filtering** - Filter by specific columns
- **Value-based Filtering** - Filter by specific values
- **Multiple Criteria** - Apply multiple filter criteria simultaneously
- **Dynamic Filtering** - Real-time filtering as you type

## Template Structure

### Excel Template Components

Structured Excel templates for data consistency:

- **Point Description Keys Sheet** - Dedicated worksheet for PDK data
- **Figure Prefix DB Sheet** - Dedicated worksheet for Figure Prefix Database
- **Property Columns** - Structured columns for all survey standards properties
- **Validation Rules** - Built-in validation for data integrity
- **Metadata Fields** - Additional information for tracking and management

### Template Validation

Ensure data integrity:

- **Structure Validation** - Verify Excel structure matches template
- **Data Type Validation** - Check data types are correct
- **Required Field Validation** - Ensure all required fields have values
- **Relationship Validation** - Verify relationships between data elements

## Conflict Resolution

### Import Conflict Handling

Handle conflicts during Excel import:

- **Conflict Detection** - Identify conflicts between existing and imported data
- **User Choice** - Choose to replace existing data or retain current settings
- **Selective Resolution** - Handle conflicts on a case-by-case basis
- **Data Preservation** - Ensure no data is lost during conflict resolution

### Conflict Resolution Process

1. **Conflict Identification** - Tool identifies conflicts between existing and imported data
2. **User Prompt** - System asks if you want to replace existing data with imported data
3. **Choice Options**:
   - **Replace** - Replace existing data with imported data
   - **Retain** - Keep existing data and skip imported data
4. **Confirmation** - Confirm your choice to proceed
5. **Update** - System updates data based on your selection

## Workflow Examples

### Example 1: Basic Excel Export/Import

1. **Export to Excel** - Export current survey standards to Excel
2. **Edit in Excel** - Modify data in Excel environment
3. **Import Back** - Import modified data to the tool
4. **Handle Conflicts** - Resolve any conflicts with existing data
5. **Apply Changes** - Apply modifications to target files

### Example 2: Excel Import with Editing

1. **Import Excel File** - Load data from Excel spreadsheet
2. **Add Missing Columns** - Add layer columns if needed
3. **Edit Data** - Modify values before applying
4. **Handle Conflicts** - Resolve conflicts with existing data
5. **Apply Changes** - Import modified data to target files

### Example 3: Search and Filter Workflow

1. **Import Large Dataset** - Load large Excel dataset
2. **Use Search** - Find specific items using search function
3. **Apply Filters** - Filter data by specific criteria
4. **Edit Filtered Data** - Modify filtered data as needed
5. **Apply Changes** - Import modified data to target files

## Best Practices

### Excel Workflow
- **Use Templates** - Use structured Excel templates for consistency
- **Validate Data** - Check Excel data before importing
- **Maintain Structure** - Preserve Excel structure during editing
- **Test Imports** - Verify Excel imports work correctly

### Data Management
- **Backup Original Data** - Keep backups of original Excel files
- **Version Control** - Maintain different versions of Excel files
- **Documentation** - Document Excel modifications and changes
- **Testing** - Test Excel workflows before large-scale operations

### Import Process
- **Verify Source Data** - Ensure Excel data is valid and complete
- **Check Data Structure** - Verify Excel structure matches requirements
- **Validate Before Import** - Check data integrity before importing
- **Handle Conflicts** - Resolve conflicts appropriately 
