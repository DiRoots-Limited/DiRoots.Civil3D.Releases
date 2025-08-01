---
layout: default
title: Transfer Survey Standards User Guide
nav_order: 10
has_children: true
permalink: /docs/transfer-survey-standards-user-guide
---

# Transfer Survey Standards User Guide

Learn how to use Transfer Survey Standards to transfer Civil 3D survey standards data between projects and manage Point Description Keys and Figure Prefix Database with Excel export and import capabilities.
{: .fs-6 .fw-300 }

## Description

Transfer Survey Standards helps you transfer your Civil 3D survey standards data between projects and manage Point Description Keys and the Figure Prefix Database, including their associated data. Whether you're transferring configuration across projects, standardizing survey standards, or using a survey standard across different projects, this tool provides efficient transfer solutions with Excel export and import functionality.

**Key Features:**
- **Transfer Settings and PDKs** - Transfer Point Description Keys between files
- **Figure Prefix Database Management** - Transfer and manage figure prefix databases
- **Multiple Source Options** - Transfer from open files, closed files, or Excel spreadsheets
- **Data Editing Capabilities** - Modify values before importing or applying
- **Conflict Resolution** - Handle conflicts between existing and imported data
- **Excel Export/Import** - Export to Excel for external editing and import back
- **Search and Filter** - Quickly find specific data in large datasets
- **Layer Validation** - Warning system for missing layer definitions

## Getting Started

### Main Interface

The Transfer Survey Standards tool has a user interface very similar to Transfer Object Layers, providing a familiar experience for users. The tool enables you to transfer settings, PDKs (Point Description Keys), and Figure Prefix Database between files to help standardize survey standards across projects.

### Transfer Sources

The tool supports multiple transfer sources:

- **Open Files** - Transfer data from currently open Civil 3D files
- **Closed Files** - Transfer data from closed Civil 3D files without opening them
- **Excel Spreadsheets** - Import data from Excel files for external editing

### Basic Workflow

1. **Open Transfer Survey Standards** from the DiRoots tab
2. **Choose Transfer Source** - Select from open files, closed files, or Excel
3. **Import Data** - Load survey standards data from the source
4. **Edit Data** (if needed) - Modify values before applying
5. **Apply Changes** - Transfer data to target files
6. **Handle Conflicts** - Resolve any conflicts between existing and imported data

## Transfer Capabilities

### Point Description Keys (PDKs)

Transfer Point Description Keys between projects:

- **Complete Transfer** - Transfer all PDK configurations
- **Selective Transfer** - Choose specific PDKs to transfer
- **Property Preservation** - Maintain all key properties during transfer
- **Conflict Resolution** - Handle conflicts between existing and imported PDKs

### Figure Prefix Database

Manage Figure Prefix Database across projects:

- **Database Transfer** - Transfer complete or partial Figure Prefix Database
- **File-based Storage** - Work with .fdb files and Excel exports
- **Data Validation** - Ensure database integrity during transfer
- **External Editing** - Export to Excel for external modification

## Advanced Features

### Data Editing Before Import

Modify data before applying to target files:

- **Pre-import Editing** - Edit values before importing
- **Column Management** - Add or modify columns as needed
- **Data Validation** - Check data integrity before import
- **Bulk Modifications** - Make changes to multiple items simultaneously

### Conflict Resolution

Handle conflicts between existing and imported data:

- **Conflict Detection** - Identify conflicts between existing and imported data
- **User Choice** - Choose to replace existing data or retain current settings
- **Selective Resolution** - Handle conflicts on a case-by-case basis
- **Data Preservation** - Ensure no data is lost during conflict resolution

### Excel Integration

Comprehensive Excel export and import capabilities:

- **Export to Excel** - Export data for external editing
- **Import from Excel** - Import modified data back to the tool
- **Template Support** - Use structured Excel templates
- **Data Validation** - Validate Excel data before import

### Search and Filter

Quickly locate specific data:

- **Search Functionality** - Find specific items in large datasets
- **Filter Options** - Filter data by various criteria
- **Efficient Navigation** - Quickly locate and modify specific items
- **Data Organization** - Organize data for easier management

## Workflow Examples

### Example 1: Transfer from Open File

1. **Open Transfer Survey Standards** from the DiRoots tab
2. **Select "Open Files"** as transfer source
3. **Choose Source File** - Select the file containing survey standards
4. **Import Data** - Load PDKs and Figure Prefix Database
5. **Review Data** - Check imported data for accuracy
6. **Apply Changes** - Transfer to target files

### Example 2: Excel Import with Editing

1. **Select "Excel"** as transfer source
2. **Import Excel File** - Load data from Excel spreadsheet
3. **Add Missing Columns** - Add layer columns if needed
4. **Edit Data** - Modify values before applying
5. **Handle Conflicts** - Resolve any conflicts with existing data
6. **Apply Changes** - Import modified data to target files

### Example 3: Figure Prefix Database Management

1. **Access Figure Prefix DB Tab** - Navigate to database management
2. **Locate Database File** - Find the .fdb file location
3. **Read Database** - Load database data into the interface
4. **Export to Excel** - Export for external editing
5. **Import Modified Data** - Import changes back to the tool
6. **Apply Changes** - Update database in target files

## Best Practices

### Data Preparation
- **Verify Source Data** - Ensure source files contain valid survey standards
- **Check Layer Definitions** - Verify required layers exist in target files
- **Validate Data Structure** - Check data integrity before transfer
- **Backup Original Data** - Keep backups of original configurations

### Transfer Process
- **Start with Small Transfers** - Begin with limited data sets
- **Test Transfers** - Verify transfers work correctly before large-scale operations
- **Document Changes** - Keep records of transferred configurations
- **Validate Results** - Check that transfers completed successfully

### Conflict Management
- **Review Conflicts** - Carefully examine conflict resolution options
- **Choose Appropriate Action** - Select replace or retain based on project needs
- **Document Decisions** - Record conflict resolution choices
- **Verify Outcomes** - Confirm that conflict resolution worked as expected

### Excel Workflow
- **Use Templates** - Use structured Excel templates for consistency
- **Validate Excel Data** - Check Excel data before importing
- **Maintain Structure** - Preserve Excel structure during editing
- **Test Imports** - Verify Excel imports work correctly 
