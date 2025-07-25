---
layout: default
title: Export and Import Excel
parent: Transfer Object Layers User Guide
nav_order: 3
---

# Export and Import Excel
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Export and Import to Excel

Transfer Object Layers provides comprehensive Excel export and import functionality using structured templates, enabling you to transfer Civil 3D object layer data efficiently and maintain data integrity.

### Excel Export Features
- **Structured Templates:** Pre-formatted Excel templates for consistent data structure
- **Complete Data Export:** Export all object layer settings and properties
- **Multiple Formats:** Support for various Excel formats (.xlsx, .xls, .csv)
- **Template Customization:** Customize export templates for specific needs

### Steps to Export to Excel
1. **Select Source:** Choose the Civil 3D file containing the object layer settings
2. **Choose Template:** Select the appropriate Excel template for your data
3. **Configure Export:** Set export options and data selection
4. **Generate File:** Create the Excel file with structured data
5. **Review Output:** Verify the exported data structure and content

![Transfer Object Layers export to Excel](../../../assets/images/TransferObjectLayers/TOL-ExportExcel.gif)
<sub>Note: the version on the image may not reflect the latest version of Transfer Object Layers.</sub>

### Excel Import Features
- **Template Validation:** Validate imported data against template structure
- **Data Mapping:** Map Excel data to Civil 3D object layer settings
- **Error Handling:** Identify and resolve import errors
- **Batch Import:** Import multiple Excel files simultaneously

### Steps to Import from Excel
1. **Select Template:** Choose the Excel template format for import
2. **Load File:** Select the Excel file containing object layer data
3. **Validate Data:** Review and validate the imported data structure
4. **Map Settings:** Map Excel data to target Civil 3D objects
5. **Apply Changes:** Import the settings to the target file

![Transfer Object Layers import from Excel](../../../assets/images/TransferObjectLayers/TOL-ImportExcel.gif)
<sub>Note: the version on the image may not reflect the latest version of Transfer Object Layers.</sub>

### Template Structure
- **Object Type Sheets:** Separate worksheets for different Civil 3D object types
- **Property Columns:** Structured columns for layer properties and settings
- **Validation Rules:** Built-in validation for data integrity
- **Metadata Fields:** Additional information for tracking and management

### Benefits
- Standardized data transfer using structured templates
- External editing capabilities in familiar Excel environment
- Data validation and error checking during import
- Collaboration and sharing of layer settings across teams 
