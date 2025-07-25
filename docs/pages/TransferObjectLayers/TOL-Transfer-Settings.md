---
layout: default
title: Transfer Settings
parent: Transfer Object Layers User Guide
nav_order: 2
---

# Transfer Settings
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Transferring Object Layer Settings

Transfer Object Layers enables you to transfer Civil 3D object layer settings between projects, whether the source files are open or closed, while preserving all properties and layer configurations.

### Transfer Capabilities
- **Open Files:** Transfer settings from currently open Civil 3D drawings
- **Closed Files:** Transfer settings from closed Civil 3D files without opening them
- **Multiple Sources:** Transfer from multiple source files simultaneously
- **Selective Transfer:** Choose specific object types and layer settings to transfer

### Steps to Transfer Settings
1. **Select Source:** Choose the source Civil 3D file (open or closed)
2. **Select Destination:** Choose the target file where settings will be applied
3. **Configure Transfer:** Select which object layer settings to transfer
4. **Review and Confirm:** Review the transfer configuration before proceeding
5. **Execute Transfer:** Apply the settings to the destination file

![Transfer Object Layers transfer settings](../../../assets/images/TransferObjectLayers/TOL-TransferSettings.gif)
<sub>Note: the version on the image may not reflect the latest version of Transfer Object Layers.</sub>

### Supported Object Types
- **Alignment Objects:** Alignment layer settings and properties
- **Profile Objects:** Profile layer configurations
- **Surface Objects:** Surface layer settings and display properties
- **Pipe Networks:** Pipe and structure layer assignments
- **Corridors:** Corridor layer settings and component assignments
- **Other Civil 3D Objects:** All standard Civil 3D object types

### Transfer Options
- **Complete Transfer:** Transfer all object layer settings
- **Selective Transfer:** Choose specific object types or settings
- **Property Mapping:** Map properties between different naming conventions
- **Conflict Resolution:** Handle conflicts between existing and transferred settings

### Benefits
- Maintain consistency across multiple projects
- Standardize layer settings across teams
- Preserve all object properties during transfer
- Work with both open and closed files efficiently 