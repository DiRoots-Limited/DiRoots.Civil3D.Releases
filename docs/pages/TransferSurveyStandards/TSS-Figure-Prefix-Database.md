---
layout: default
title: Figure Prefix Database
parent: Transfer Survey Standards User Guide
nav_order: 2
---

# Figure Prefix Database
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Figure Prefix Database

Transfer Survey Standards provides comprehensive tools for managing the Figure Prefix Database, allowing you to transfer, edit, and maintain figure prefix configurations across multiple Civil 3D projects. The tool works with file-based databases and Excel integration.

## Overview

The Figure Prefix Database is a critical component of Civil 3D survey standards that defines how survey figures are displayed and managed. Unlike Point Description Keys, the Figure Prefix Database data is fixed and stored in dedicated files (.fdb files). The Transfer Survey Standards tool enables you to read, modify, and transfer these database configurations.

## File-Based Database Management

### Database File Location

The Figure Prefix Database is stored in dedicated files:

- **Default Location** - Database files are stored in specific system locations
- **File Format** - Uses .fdb file format for database storage
- **Data Reading** - Tool can read all database data and display it in the UI
- **File Management** - Locate and manage database files efficiently

### Database Access

Access and manage Figure Prefix Database files:

1. **Navigate to Figure Prefix DB Tab** - Access database management interface
2. **Locate Database File** - Find the .fdb file in the system
3. **Read Database** - Load database data into the tool interface
4. **View Data** - Examine all database entries and configurations
5. **Modify Data** - Edit database entries as needed

![Transfer Survey Standards figure prefix database](../../../assets/images/TransferSurveyStandards/TSS-FigurePrefixDatabase.gif)
<sub>Note: the version on the image may not reflect the latest version of Transfer Survey Standards.</sub>

## Excel Integration

### Export to Excel

Export Figure Prefix Database for external editing:

- **Excel Export** - Export database data to Excel format
- **External Editing** - Modify data in familiar Excel environment
- **Data Preservation** - Maintain all database structure and relationships
- **Template Support** - Use structured Excel templates for consistency

### Import from Excel

Import modified data back to the tool:

- **Excel Import** - Import modified data from Excel files
- **Data Validation** - Validate imported data before applying
- **Change Application** - Apply modifications to database
- **Error Handling** - Handle import errors and data conflicts

### Excel Workflow

Complete Excel-based editing workflow:

1. **Export to Excel** - Export current database to Excel
2. **External Editing** - Modify data in Excel
3. **Import Back** - Import modified data to the tool
4. **Apply Changes** - Apply modifications to target files
5. **Validation** - Verify changes are applied correctly

## Database Components

### Fixed Data Structure

The Figure Prefix Database has a fixed structure:

- **Prefix Codes** - Unique identifiers for different figure types
- **Descriptions** - Human-readable descriptions of figure types
- **Line Types** - Line type assignments for figure components
- **Layers** - Layer assignments for different figure elements
- **Styles** - Annotation and display style configurations

### Data Management

Unlike PDKs, Figure Prefix Database data is fixed:

- **No Preferences Tab** - Figure Prefix DB tab doesn't have preferences
- **Fixed Structure** - Database structure is predefined
- **File-based Storage** - Data is stored in .fdb files
- **Complete Data Access** - Tool can read and display all database data

## Transfer Options

### Database Transfer Methods

Multiple ways to transfer Figure Prefix Database:

- **File-based Transfer** - Transfer complete database files
- **Excel Export/Import** - Use Excel for external editing and transfer
- **Selective Transfer** - Choose specific prefixes or categories
- **Merge Operations** - Combine databases from multiple sources

### Transfer Process

Complete transfer workflow:

1. **Access Database** - Navigate to Figure Prefix DB tab
2. **Locate Source** - Find source database file (.fdb)
3. **Read Data** - Load database data into interface
4. **Export to Excel** (optional) - Export for external editing
5. **Import Data** - Import modified or original data
6. **Apply Changes** - Transfer to target files

## Advanced Features

### Data Validation

Ensure database integrity:

- **Structure Validation** - Verify database structure is correct
- **Data Integrity** - Check for missing or invalid data
- **Relationship Validation** - Ensure relationships between components are valid
- **Error Detection** - Identify and resolve database errors

### Database Comparison

Compare different Figure Prefix Databases:

- **Database Analysis** - Compare databases from different sources
- **Difference Identification** - Identify differences between databases
- **Merge Planning** - Plan database merges and updates
- **Conflict Resolution** - Resolve conflicts between databases

### Bulk Operations

Efficient database management:

- **Batch Processing** - Apply changes to multiple prefixes simultaneously
- **Data Import** - Import large datasets efficiently
- **Validation Tools** - Validate multiple database entries
- **Error Reporting** - Comprehensive error reporting for bulk operations

## Workflow Examples

### Example 1: Basic Database Transfer

1. **Access Figure Prefix DB Tab** - Navigate to database management
2. **Locate Database File** - Find the .fdb file location
3. **Read Database** - Load database data into the interface
4. **Review Data** - Examine database entries and configurations
5. **Apply Changes** - Transfer database to target files

### Example 2: Excel-based Editing

1. **Export to Excel** - Export current database to Excel
2. **Edit in Excel** - Modify database entries in Excel
3. **Import Modified Data** - Import changes back to the tool
4. **Validate Changes** - Verify modifications are correct
5. **Apply to Target** - Transfer modified database to target files

### Example 3: Database Comparison

1. **Load Source Database** - Load first database for comparison
2. **Load Target Database** - Load second database for comparison
3. **Compare Data** - Identify differences between databases
4. **Plan Merges** - Plan how to merge or update databases
5. **Execute Transfer** - Apply planned changes to target database

## Best Practices

### Database Management
- **Backup Original Files** - Keep backups of original .fdb files
- **Version Control** - Maintain different versions of databases
- **Documentation** - Document database changes and modifications
- **Testing** - Test database transfers before large-scale operations

### Excel Workflow
- **Use Templates** - Use structured Excel templates for consistency
- **Validate Data** - Check Excel data before importing
- **Maintain Structure** - Preserve database structure during editing
- **Test Imports** - Verify Excel imports work correctly

### Transfer Process
- **Verify Source Data** - Ensure source database is valid and complete
- **Check Target Compatibility** - Verify target files can accept database
- **Test Transfers** - Test transfers with small datasets first
- **Validate Results** - Confirm transfers completed successfully 
