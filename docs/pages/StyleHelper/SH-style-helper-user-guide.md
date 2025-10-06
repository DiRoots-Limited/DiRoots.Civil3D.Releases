---
layout: default
title: Style Helper User Guide
nav_order: 7
has_children: true
permalink: /docs/style-helper-user-guide
---

# Style Helper User Guide

Learn how to use Style Helper to efficiently edit Civil 3D object styles, label styles, table styles and their associate style components directly from the interface with bulk editing capabilities.

<img src="{{ '/assets/images/logos/StyleHelperLight.png' | relative_url }}" alt="Style Helper Logo" width="128" style="display:block;margin:0 auto;">

{: .fs-6 .fw-300 }

## Overview

Style Helper provides a interface for editing Civil 3D object styles, label styles, and table styles and their associated object components. The tool features custom column configuration based on selected objects, support for parent-child relationship label styles, and bulk editing capabilities.

**Key Features:**
- **Style Data Support** - Edit and displays the Object styles, Label styles, Table styles in a table format interface
- **Label Component Properties Editing Support** - The tool supports component properties edition
- **Multi-Object Bulk Editing** - Edit multiple objects simultaneously in table format
- **Children Nested Label Style Support** - The tool supports children nested label syles properties edition
- **Customizable Data Display** - Configure table columns to show the data you need
- **Profile System** - Save and reuse column configurations

## Getting Started

### Main Interface

Style Helper provides three main tabs for different style types:

- **Object Styles Tab** - Edit Civil 3D object styles (e.g. Surface Styles)
- **Label Styles Tab** - Edit Civil 3D label styles (e.g. Point Label Styles)
- **Table Styles Tab** - Edit Civil 3D table styles (e.g. Point Table Styles)

> **GIF Placeholder:** Show the main interface showing the three-tab structure

### Basic Workflow

1. **Open Style Helper** from the DiRoots tab
2. **Go to Type of Data Tab** - Select Object Styles, Label Styles, or Table Styles tab
3. **Check Objects** - Check objects in the Civil 3D tree structure to filter table data
4. **Configure Columns** - Use Preferences button to add, remove, or reorder table columns
5. **Edit Data** - Modify style data directly in the table where possible. Some data cannot be modified as it is read-only.
6. **Save Profile** - Save column configurations for reuse

> **GIF Placeholder:** Demonstrate the complete workflow from opening to saving a profile

## Documentation Structure

This user guide is organized into the following sections:

- **[Tabs Overview](SH-Three-Tabs-Overview.md)** - Explanation of the three tabs and Civil 3D structure with component column reference
- **[Editing Features](SH-Editing-Features.md)** - Table customization, data editing for all tabs, batch editing, and children styles support
- **[Profile](SH-Profile.md)** - Profile management for saving and reusing column configurations

