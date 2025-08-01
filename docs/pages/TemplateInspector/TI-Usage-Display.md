---
layout: default
title: Usage Display
parent: Template Inspector User Guide
nav_order: 3
---

# Usage Display
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Displaying Object Usage Status

Template Inspector clearly displays whether objects are used or not, helping you make informed decisions about which objects can be safely deleted.

### Usage Status Indicators
- **Used:** Object is actively used in the file (colored green)
- **Not Used:** Object is not referenced anywhere (colored red)
- **Partially Used:** Object has some usage but may be safe to delete (colored yellow)

### Understanding Usage Display
1. **Used Objects:** These objects have dependencies and should not be deleted without reassignment
2. **Unused Objects:** These objects can be safely deleted to clean up your file
3. **Usage Count:** Shows how many times each object is referenced

![Template Inspector usage display](../../../assets/images/TemplateInspector/TI-UsageDisplay.gif)
<sub>Note: the version on the image may not reflect the latest version of Template Inspector.</sub>

### Making Deletion Decisions
- Objects marked as "Not Used" can be safely deleted
- Objects marked as "Used" require reassignment before deletion
- Review usage details to understand dependencies before taking action 
